
# Отчёт о выполнении задания "Книжный интернет-магазин" по дисциплине "Основы кибериммунных систем"
Состав команды:

1. Туктин Константин Владимирович (3 курс - ИВТ-21-22 ФГБОУ ВО ЧГУ)
2. Лоскутова Кристина Владимировна (3 курс - ИВТ-22-22 ФГБОУ ВО ЧГУ)
3. Васькина Анастасия Дмитриевна (3 курс - ИВТ-21-22 ФГБОУ ВО ЧГУ)
4. Ефимов Андрей Юрьевич (3 курс - ИВТ-21-22 ФГБОУ ВО ЧГУ)

***
СОДЕРЖАНИЕ РАБОТЫ
***
(здесь будет содержание)

## Введение 

### Описание книжного интернет-магазина  "Я люблю читать!"

Книжный интернет-магазин  "Я люблю читать!" — это интерактивный сайт с каталогом, в котором представляются товары в виде книг, а также корзина для формирования заказа.

Основная цель магазина: предоставить пользователям удобный и безопасный способ приобретения книг, как в электронном, так и в физическом формате, с максимальной защитой персональных данных и финансовой информации.

Основные задачи интернет-магазина:
1. **Предоставление каталога книг**: магазин будет позволять пользователям просматривать, фильтровать и искать книги по различным категориям, таким как жанр, автор, цена, новизна и т.д.
2. **Обеспечение управления пользователями**: сайт будет требовать создания личного кабинета для каждого пользователя, где можно управлять своими покупками, отслеживать историю заказов и сохранять книги в избранное.
3. **Оформление заказов и обработка платежей**: ресурс предоставляет возможность добавлять книги в корзину и оформлять заказы через простую и безопасную процедуру.
4. **Предотсавление возможности осуществления доставки**: магазин будет предлагать различные варианты доставки (для физических книг) и моментальный доступ к цифровым версиям книг (электронные и аудиокниги).
5. **Обратная связь**: предоставление возможности оставить отзыв или оценку для каждой книги, что помогает другим покупателям принимать решение.
6. **Поддержка**: интеграция службы поддержки, которая будет помогать пользователям решать вопросы, связанные с заказами, доставкой и техническими проблемами.

### Постановка задачи

Необходимо разработать архитектуру для web-приложения для описанного выше книжного интернет-магазина, задача которого: эффективно управлять каталогом книг, позволяя клиентам выбирать и покупать необходимые книги. Web-ресурс должен включать как десктопную, так и мобильную реализации, а также базу данных, хранящую персональные данные клиентов.

### Цели и Предположения Безопасности (ЦПБ)

В качестве целей безопасности можем выделить следующие пункты:
1. Обспечение целостности персональных данных при обработке и передаче
2. Предоставление доступа к персональным данным только авторизованным пользователям в нужное время
3. Применение принципа минимально необходимого доступа (least privilege) для сотрудников и систем
4. Обсепечение защиты данных о платеже от перехвата, искажения или подмены
5. Обеспечение доступности интернет-магазина без ощутимых задержек (не более 10 секунд)
6.  Наличие стабильной системы мониторинга производительности и безопасности
7.  Только авторизованные пользователи имеют возможность инициировать транзакции

Предположения безопасности:
1. Сотрудники компании, имеющие доступ к конфиденциальной информации, обладают достаточной квалификацией, профессионализмом и следуют корпоративным политикам безопасности
2. Оборудование, используемое для хранения данных и работы сервисов, надёжно, не содержит уязвимостей на аппаратном уровне и способно обрабатывать большое количество данных одновременно
3. Дата-центры, где хранится оборудование и данные, находятся под физической охраной и защищены от несанкционированного доступа, а также от природных и техногенных катастроф
4. Интернет-каналы и сетевые инфраструктуры, через которые осуществляется обмен данными, защищены от перехвата данных

### Защищаемые ценности
| Ценность | Негативное событие | Оценка ущерба | Комментарии | Цели безопасности |
|----------|----------|----------| -------------- | ------- |
| Персональные данные клиентов  |  Утечка персональных данных клиентов (имена, адреса и номера телефонов и др.) | Высокий   | Падение доверия клиентов;</br>Нарушение законодательства |  1, 2, 3, 6  |
| Финансовые транзакции    |  Кража данных платёжных карт клиентов в процессе оформления покупки  | Высокий   | Нарушение законодательтсва | 4, 7, 6 |
| Интеллектуальная собственность | Пиратский доступ к электронной библиотеке магазина, бесплатное распространение электронных версий книг   | Средний   |  | |
| Конфиденциальность коммуникаций | Уязвимость в системе обмена сообщениями службы поддержки | Средний  |   | |
| Доступность сервиса  | DDoS-атака, которая делает сайт магазина недоступным на несколько дней   | Высокий | Потеря продаж   | 5, 6   |
| Физическое оборудование (сисема хранения данных)   | Повреждение серверов в результате физического пореждения   | Высокий   | Полная потеря доступа к системе   | 6 |
| Данные корзины  | Утечка истории покупок клиентов, включая информацию о заказах, предпочтениях и адресах доставки.   |  Средний    |    |     |

## Архитектура интернет-магазина

### Компоненты решения

| Компонента  |  Описание компоненты  |
|---|-------|
| База данных (Database) | Хранилище данных интернет-магазина. Здесь могут храниться книги, пользователи, заказы и другие объекты, необходимые для работы веб-сервиса. |
| Представление (View) | Охватывает пользовательский интерфейс и логику представления веб-сайта. Он отвечает за отображение данных и представление их пользователю. Оно также может отправлять пользовательский ввод обратно Контроллеру для дальнейшей обработки. Не обрабатывает введённые данные пользователя. |
| Модель (Model) |  Предоставляет данные и методы работы с ними: запросы в базу данных, проверка на корректность. Модель не зависит от отображения (не знает как данные визуализировать) и контроллера (не имеет точек взаимодействия с пользователем), просто предоставляя доступ к данным и управлению ими. |
| Контроллер (Controller)  | Действует как интерфейс между Моделью и Представлением, используя их для выполнения необходимого дейтсвия. Контролирует и направляет данные от пользователя к системе и наоборот. |
| Платёжный шлюз (Payment Gateway Integration) | Обрабатывает транзакции с использованием кредитных карт, банковских переводов или других электронных платёжных систем (например, PayPal, Stripe, Square). Принимать платёжные данные (номер карты, срок действия, CVV и т.д.) и передавать их на обработку онлайн-банку. | 

### Описание алгоритмов взаимодействия
При получении информации о товаре (книге) или электронной версии книги:
1. Пользователь создаёт запрос, нажимая на кнопку или вводя данные в форму через компонент Представление (View).
2. Запрос передаётся Контроллеру (Controller).
3. Контроллер интерпретирует действия пользователя и решает, какие операции нужно выполнить.
4. Контроллер использует компонент Модель (Model) для выполнения бизнес-логики или работы с данными, передавая или принимая их.
5. Модель выполняет операции с данными, непосредственно хранящимися в базе данных (например, читает данные из базы, изменяет их или записывает).
6. После успешного выполнения операции Модель возвращает результат или обновлённые данные обратно в Контроллер.
7. Контроллер получает обновлённые данные от Модели и решает, какое Представление нужно отобразить пользователю.
8. Контроллер передаёт данные в Представление, которое генерирует обновлённый интерфейс для пользователя, возможно с новыми данными или результатами действий.
9. Представление отображает результаты выполнения действий пользователю, обновляя страницу или интерфейс с новыми данными.

При осуществлении покупки: 
1. Пользователь переходит на страницу покупки товара (например, корзину) и заполняет необходимые поля в форме страницы.
2. После того как пользователь нажимает кнопку "Оформить заказ", все введённые данные передаются в Контроллер.
3.  Контроллер отправляет платёжную информацию через защищённое соединение на внешний платёжный шлюз.
4.  Платёжный шлюз проверяет правильность платёжных реквизитов, взаимодействует с банком или другим финансовым учреждением для авторизации транзакции.
5.  Банк, выпустивший карту, проверяет валидность карты, баланс пользователя и одобряет или отклоняет транзакцию. Ответ возвращается платёжному шлюзу.
6.  Контроллер получает ответ от платёжного шлюза. Если транзакция прошла успешно, информация о заказе обновляется — заказ помечается как оплаченный, в базу данных записывается статус транзакции через компонент Модель.
7.  На основании полученного ответа от платёжного шлюза Контроллер формирует данные для отправки компоненту Представление.
8.  Пользователю отображается страница с результатами транзакции.
***
### Схема взаимодействия компонентов интернет-магазина (до кибериммунизации)
![изображение](https://github.com/kostya1962/Cyberimmunity/blob/main/Struct%20of%20website.jpg)
***
### Описание сценариев (последовательности выполнения операций), при которых ЦБ нарушаются

**Сценарий №1**

Компроментация персональных данных клиентов:
1. Пользователь отправляет персональные данные через форму на сайте.
2. Данные передаются по незащищенному каналу (например, HTTP).
3. Злоумышленник перехватывает данные в процессе передачи.
4. Данные станоятся доступными злоумышеннику, а также искажаются или изменяются.
5. На сервер попадают некорректные сведения и персональные данные клиента переходят третьим лицам.

**Сценарий №2**

Несанкционированное получение доступа к учтёной записи пользователя:
1. Для проверки прав доступа к учтёной записи клиента система использует однофакторную аутентификацию.
2. При регистрации в онлайн-портале пользователь с большой вероятностю использует слабый пароль или пароль, который был использован для аутентификации на другой платформе.
3. Злоумышленник применяет подстановку учётных данных, собранных с других аккаунтов на тех или иных платформах (credential stuffing).
4. Логин и праоль совпадают при переборе злоумышленником (бутфорс-атака).
5. Злоумышленник получает доступ к учётной записи пользователя, включая к конфиденциальные данные.

**Сценарий №3**

Незарегестрированная утечка данных:
1. В систему не встроены инструменты мониторинга и регистрации.
2. Оператор веб-сайта интернет-магазина не смог обнаружить нарушение.
3. Внешняя сторона уведомила владельца интернет-магазина, что в базе данных книг были изменены более тысячи записей о книгах, включая цены кнниг и снятие непроданных книг с продажи.
4. Проверка после инцидента показала, что разработчики веб-сайта не устранили существенные уязвимости.
5. Поскольку не было регистрации или мониторинга системы, утечка данных могла происходить довольно длительное время (несколько лет).

**Сценарий №4**

Перехват или искажение платёжной информации банковских транзакций:
1. Пользователь вводит данные о платеже на сайте.
2. Злоумышленник использует методы MITM (man-in-the-middle) для перехвата данных.
3. Данные о платеже искажаются или подменяются.
4. Финансовые потери для пользователя и интернет-магазина.

**Сценарий №5**

Зависание веб-сайта на некоторое продолжительное время (несколько минут/часов/дней):
1. Пользователь пытается зайти на сайт интернет-магазина.
2. Злоумышленник запускает DDoS-атаку на сервер.
3. Сайт становится недоступным или работает с большими задержками.
4. Пользователь не может совершить покупку, что приводит к потере
продаж.


## Кибериммунизация электронного магазина
### Описание позитивных сценариев работы

**Сценарий №1**

1. Пользователь отправляет персональные данные через защищенную
форму на сайте.
2. Данные передаются по защищенному каналу (например, HTTPS).
3. Данные шифруются перед отправкой.
4. Получатель получает целостные и защищенные данные.

**Сценарий №2**

1. Легитимный пользователь пытается получить доступ к персональным данным чужой учётной записи.
2. Система требует пройти многофакторную аутентификацию.
3. Пользователь успешно проходит проверку (например, указывает код из SMS).

**Сценарий №3**

1. Внедряется система мониторинга производительности и безопасности.
2. Система отслеживает аномалии в работе и уведомляет администраторов.
3. Администраторы оперативно реагируют на любые проблемы.
4. Инциденты предотвращаются до их возникновения.

**Сценарий №4**

1. Пользователь вводит данные о платеже на сайте.
2. Данные передаются по защищенному каналу с использованием шифрования.
3. Платёжные данные попадают на сервер.
4. Данные проверяются на целостность перед обработкой.
5. Успешное проведение банковской транзакции.
6. Отправляется подтверждение клиенту об успешной операции.

**Сценарий №5**

1. Пользователь пытается зайти на сайт интернет-магазина.
2. Система имеет резервные серверы и балансировку нагрузки.
3. Сайт работает быстро и без задержек даже в пиковые часы.
4. Пользователь может без проблем совершать покупки.

### Рекомендации по повышению безопасности web-сервиса (выполнение целей безопасности)



### Добавление необходимых модулей безопасностей



### Схема взаимодействия компонентов интернет-магазина (полсе кибериммунизации)
***
РИСУНОК
***

## Заключение



## Список использованных информационных источников




