
# Книжный интернет-магазин "Я люблю читать!"
Состав команды:

1. Туктин Константин Владимирович (3 курс - ИВТ-21-22 ФГБОУ ВО ЧГУ)
2. Лоскутова Кристина Владимировна (3 курс - ИВТ-22-22 ФГБОУ ВО ЧГУ)
3. Васькина Анастасия Дмитриевна (3 курс - ИВТ-21-22 ФГБОУ ВО ЧГУ)
4. Ефимов Андрей Юрьевич (3 курс - ИВТ-21-22 ФГБОУ ВО ЧГУ)

***
**СОДЕРЖАНИЕ РАБОТЫ**
- [Введение](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%B2%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5)
    - [Описание книжного интернет-магазина  "Я люблю читать!"](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BA%D0%BD%D0%B8%D0%B6%D0%BD%D0%BE%D0%B3%D0%BE-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0--%D1%8F-%D0%BB%D1%8E%D0%B1%D0%BB%D1%8E-%D1%87%D0%B8%D1%82%D0%B0%D1%82%D1%8C)
    - [Постановка задачи](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BF%D0%BE%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B8)
    - [Цели и Предположения Безопасности (ЦПБ)](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D1%86%D0%B5%D0%BB%D0%B8-%D0%B8-%D0%BF%D1%80%D0%B5%D0%B4%D0%BF%D0%BE%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D1%86%D0%BF%D0%B1)
    - [Защищаемые ценности](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%B7%D0%B0%D1%89%D0%B8%D1%89%D0%B0%D0%B5%D0%BC%D1%8B%D0%B5-%D1%86%D0%B5%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
- [Архитектура интернет-магазина](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0)
  - [Компоненты решения](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BA%D0%BE%D0%BC%D0%BF%D0%BE%D0%BD%D0%B5%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F)
  - [Описание алгоритмов взаимодействия](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%D0%BE%D0%B2-%D0%B2%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D1%8F)
  - [Схема взаимодействия компонентов интернет-магазина (до кибериммунизации)](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D1%81%D1%85%D0%B5%D0%BC%D0%B0-%D0%B2%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D1%8F-%D0%BA%D0%BE%D0%BC%D0%BF%D0%BE%D0%BD%D0%B5%D0%BD%D1%82%D0%BE%D0%B2-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0-%D0%B4%D0%BE-%D0%BA%D0%B8%D0%B1%D0%B5%D1%80%D0%B8%D0%BC%D0%BC%D1%83%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8)
  - [Угрозы безопасности сайта по списку OWASP](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D1%83%D0%B3%D1%80%D0%BE%D0%B7%D1%8B-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D1%81%D0%B0%D0%B9%D1%82%D0%B0-%D0%BF%D0%BE-%D1%81%D0%BF%D0%B8%D1%81%D0%BA%D1%83-owasp)
  - [Описание сценариев, при которых ЦБ нарушаются](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B5%D0%B2-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B9-%D0%BF%D1%80%D0%B8-%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D1%85-%D1%86%D0%B1-%D0%BD%D0%B0%D1%80%D1%83%D1%88%D0%B0%D1%8E%D1%82%D1%81%D1%8F)
- [Кибериммунизация электронного магазина](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BA%D0%B8%D0%B1%D0%B5%D1%80%D0%B8%D0%BC%D0%BC%D1%83%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D1%8D%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0)
  - [Описание позитивных сценариев работы](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D1%85-%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B5%D0%B2-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B)
  - [Рекомендации по повышению безопасности web-сервиса (выполнение целей безопасности)](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8-%D0%BF%D0%BE-%D0%BF%D0%BE%D0%B2%D1%8B%D1%88%D0%B5%D0%BD%D0%B8%D1%8E-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B8-web-%D1%81%D0%B5%D1%80%D0%B2%D0%B8%D1%81%D0%B0-%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5-%D1%86%D0%B5%D0%BB%D0%B5%D0%B9-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B8)
  - [Добавление модулей безопасности](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D1%8B%D1%85-%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D0%B5%D0%B9-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B5%D0%B9)
  - [Схема взаимодействия компонентов интернет-магазина](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D1%81%D1%85%D0%B5%D0%BC%D0%B0-%D0%B2%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D1%8F-%D0%BA%D0%BE%D0%BC%D0%BF%D0%BE%D0%BD%D0%B5%D0%BD%D1%82%D0%BE%D0%B2-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5-%D0%BA%D0%B8%D0%B1%D0%B5%D1%80%D0%B8%D0%BC%D0%BC%D1%83%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8)
- [Заключение](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D0%B7%D0%B0%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)
- [Список использованных информационных источников](https://github.com/kostya1962/Cyberimmunity?tab=readme-ov-file#%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D1%85-%D0%B8%D1%81%D1%82%D0%BE%D1%87%D0%BD%D0%B8%D0%BA%D0%BE%D0%B2)

***


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

Необходимо разработать архитектуру для web-приложения для описанного выше книжного интернет-магазина, задача которого: эффективно управлять каталогом книг, позволяя клиентам выбирать и покупать необходимые книги. Web-ресурс должен включать базу данных, хранящую персональные данные, а также предоставлять возможность осуществлять тарнзакции для покупки книг.
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
| Представление (View) | Отвечает за работу с пользовательским интерфейсом. Охватывает пользовательский интерфейс и логику представления веб-сайта. Он отвечает за отображение данных и представление их пользователю. Оно также может отправлять пользовательский ввод обратно Контроллеру для дальнейшей обработки. Не обрабатывает введённые данные пользователя. |
| Модель (Model) |  Отвечает за работу с данными. Предоставляет данные и методы работы с ними: запросы в базу данных, проверка на корректность. Модель не зависит от Представления (не знает как данные визуализировать) и контроллера (не имеет точек взаимодействия с пользователем), просто предоставляя доступ к данным и управлению ими. |
| Контроллер (Controller)  | Отвечает за управляющую логику. Действует как интерфейс между Моделью и Представлением, используя их для выполнения необходимого дейтсвия. Контролирует и направляет данные от пользователя к системе и наоборот. |
| Платёжный шлюз (Payment Gateway Integration) | Обрабатывает транзакции с использованием кредитных карт, банковских переводов или других электронных платёжных систем. Принимать платёжные данные (номер карты, срок действия, CVV-код и т.д.) и передавать их на обработку онлайн-банку. | 

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
![изображение](https://github.com/kostya1962/Cyberimmunity/blob/main/%D0%A1%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%20%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0.drawio%20(%D0%B4%D0%BE).svg)
***



### Угрозы безопасности сайта по списку OWASP
| Угроза  | Описание  | Перечень общих слабостей |
|----|------|-----|
| SQL-инъекции | SQL-инъекции возникают, когда злоумышленник может вставить вредоносный SQL-код в поля ввода, например, в форму поиска товаров или аутентификации | [CWE-79](https://cwe.mitre.org/data/definitions/79.html)</br>[CWE-89](https://cwe.mitre.org/data/definitions/89.html)</br>[CWE-73](https://cwe.mitre.org/data/definitions/73.html)|
| XSS (Межсайтовый скриптинг, Cross-Site Scripting)  | XSS-атаки позволяют злоумышленнику внедрить вредоносные скрипты на страницы интернет-магазина | [CWE-80](https://cwe.mitre.org/data/definitions/80.html)</br> [CWE-87](https://cwe.mitre.org/data/definitions/87.html)|
| CSRF (Межсайтовая подделка запросов, Cross-Site Request Forgery) | CSRF-атака использует авторизованную сессию пользователя для выполнения несанкционированных действий от его имени. |
| Уязвимость при неверной авторизации и аутентификации    |  Ошибки в проверке прав доступа могут позволить злоумышленникам получить доступ к страницам администратора или другим закрытым ресурсам, таким как учетные записи пользователей. |[CWE-352](https://cwe.mitre.org/data/definitions/352.html)|
| Неправильное управление сессиями (Session Hijacking)  |  Аутентификация пользователя или иное создание нового сеанса пользователя без аннулирования любого существующего идентификатора сеанса дает злоумышленнику возможность украсть аутентифицированные сеансы.  | [CWE-384](https://cwe.mitre.org/data/definitions/384.html)|
| Неправильная валидация данных (Data Validation) | Неправильная или отсутствующая валидация данных может привести к множеству уязвимостей. Например, злоумышленник может ввести некорректные данные в формы регистрации или оформления заказа, что приведёт к ошибкам в бизнес-логике приложения или даже к выполнению вредоносного кода. | [CWE-20](https://cwe.mitre.org/data/definitions/20.html)</br>[CWE-100](https://cwe.mitre.org/data/definitions/100.html)</br>[CWE-1173](https://cwe.mitre.org/data/definitions/1173.html)</br>[CWE-1174](https://cwe.mitre.org/data/definitions/1174.html)</br>[CWE-1287](https://cwe.mitre.org/data/definitions/1287.html)|
| Открытые перенаправления (Open Redirects) | Открытые перенаправления позволяют злоумышленнику перенаправить пользователя на вредоносный сайт через легитимный домен интернет-магазина. Это может быть использовано для фишинга, кражи данных или других атак. ||
| Уязвимость к отказу в обслуживании (DoS/DDoS) | Злоумышленник может отправлять чрезмерное количество запросов к серверу, перегружая систему и делая её недоступной для легитимных пользователей. Это может быть вызвано отсутствием ограничения частоты запросов или недостаточной оптимизацией запросов к базе данных.  ||
| Уязвимости в кроссдоменных запросах (CORS)  | Неправильная настройка CORS, позволяющая злоумышленникам выполнять запросы от имени пользователя.  ||
| Уязвимости в логировании и мониторинге | Недостаточное логирование действий пользователей, что затрудняет выявление атак  ||
| Уязвимости в механизмах обработки платежей | Неправильная обработка платежной информации, что может привести к мошенничеству. ||

### Описание сценариев (последовательности выполнения операций), при которых ЦБ нарушаются

**Сценарий №1**

Компрометация персональных данных клиентов:
1. Пользователь отправляет персональные данные через форму на сайте.
2. Данные передаются по незащищенному каналу (например, HTTP).
3. Злоумышленник перехватывает данные в процессе передачи.
4. Данные становятся доступными злоумышленнику, а также искажаются или изменяются.
5. На сервер попадают некорректные сведения и персональные данные клиента переходят третьим лицам.

**Сценарий №2**

Несанкционированное получение доступа к учётной записи пользователя:
1. Для проверки прав доступа к учётной записи клиента система использует однофакторную аутентификацию.
2. При регистрации в онлайн-портале пользователь с большой вероятностью использует слабый пароль или пароль, который был использован для аутентификации на другой платформе.
3. Злоумышленник применяет подстановку учётных данных, собранных с других аккаунтов на тех или иных платформах (credential stuffing).
4. Логин и пароль совпадают при переборе злоумышленником (бутфорс-атака).
5. Злоумышленник получает доступ к учётной записи пользователя, включая к конфиденциальные данные.

**Сценарий №3**

Незарегистрированная утечка данных:
1. В систему не встроены инструменты мониторинга и регистрации.
2. Оператор веб-сайта интернет-магазина не смог обнаружить нарушение.
3. Внешняя сторона уведомила владельца интернет-магазина, что в базе данных книг были изменены более тысячи записей о книгах, включая цены книг и снятие непроданных книг с продажи.
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

**Защита от атак на основе данных:**
- Шифрование данных при передаче: все данные, передаваемые между клиентом и сервером (данные о заказах, оплате), должны быть зашифрованы с использованием протокола HTTPS. Необходимо настроить сертификаты SSL/TLS с актуальным уровнем шифрования.
- Шифрование данных в состоянии покоя: все хранимые данные (пароли пользователей, данные о платежах) должны быть зашифрованы с использованием современных алгоритмов. Важно использовать соли для хеширования паролей, чтобы предотвратить атаки с использованием словарей.
- Проверка целостности данных: используются методы проверки подлинности и целостности данных для предотвращения подмены или искажения данных, передаваемых между клиентом и сервером.
- Безопасное хранение API-ключей: все API-ключи, используемые для интеграции с внешними сервисами (платежными системами), должны быть надежно защищены и храниться в защищенных хранилищах.  Управление паролями: вводится надежная система управления паролями, включающая сложные политики для паролей пользователей. Используется надежный алгоритм хеширования паролей (bcrypt).
- Регулярный аудит данных: проводятся регулярные проверки целостности данных и соответствия политикам безопасности.

**Защита от атак на веб-приложение:**
- Внедрение защитных механизмов: реализуются меры защиты от распространённых атак, таких как SQL-инъекции, XSS, CSRF и атаки на основе фреймворков, с помощью проверки вводимых данных, параметризованных запросов и других инструментов.
- Применение веб-аппликационных файрволов (WAF): WAF используется для защиты веб-приложений от различных типов атак.
- Белый и чёрный списки IP-адресов: используется список доверенных IP-адресов и блокировка нежелательных IP-адресов.
- Анализ журналов и предупреждений: настройка системы мониторинга и ведения журналов для выявления подозрительной активности и уязвимостей.
- Защита от атак методом перебора паролей: внедряются механизмы защиты от таких атак, включая блокировку учетных записей после нескольких неудачных попыток входа.
- Снижение риска раскрытия данных: ограничение доступа к информации, хранящейся в базе данных, с применением принципа наименьших привилегий.

**Защита от компрометации сервера:**
- Регулярное обновление программного обеспечения: регулярное обновление операционной системы, веб-сервера, баз данных и других компонентов для установки последних обновлений, устраняющих уязвимости.
- Мониторинг состояния сервера: внедряется система мониторинга состояния серверов для быстрого реагирования на проблемы.
- Управление доступом к серверу: ограничение доступа к серверу только авторизованным пользователям с минимальными привилегиями.
- Защита от DDoS-атак: внедрение механизмов защиты от распределённых атак типа «отказ в обслуживании» (DDoS).

**Соответствие нормам и стандартам:**
- Соответствие требованиям законодательства: обеспечение соответствия всем применимым нормам и стандартам (GDPR, PCI DSS).
- Политики безопасности: разработка и внедрение подробных политик безопасности, охватывающих все аспекты работы веб-сервиса.

### Добавление необходимых модулей безопасностей

**Клиентская сторона (Frontend):**

Технологии: React,, Vue.js с HTML и CSS.

Пользовательский интерфейс для просмотра книг, добавления их в корзину, просмотр личного кабинета, истории заказов, управления профилем, платных подписок, поиска книг и рекомендаций. Включает обработку корзины, оплату (интегрированную с платежными системами: банковская карта, сбп), регистрацию/авторизацию с использованием JWT и двухфакторной аутентификации (2FA), обратную связь. Обеспечивается защищенная передача данных с использованием HTTPS (TLS/SSL).

**Серверная часть (Backend):**

Технологии: Node.js с Express.js 

Обеспечивает обработку заказов (создание, изменение, удаление), управление пользователями (регистрация, аутентификация, профили), управление книжным каталогом (добавление, редактирование, удаление, фильтрование), интеграцию с платежными системами, обработку платежей, обработку отзывов и обращений. 

**База данных (Данные):**

Технологии: PostgreSQL.

Отвечает за хранение данных о книгах, пользователях, заказах, платежах, транзакциях. Поддержка транзакций для целостности данных, индексы для быстроты запросов, разделение данных для разных ролей (шифрование паролей) и регулярные резервные копии.

**Платежная система (МИР, Visa):**

Технологии: API платежных систем (SberBusinessAPI).

Позволит обрабатывать платежей, проверять платежи, обработывать ошибоки, обеспечить безопасность платежной информации (HTTPS).

**Модули безопасности:**
1. **Авторизация и аутентификация**: JWT, двухфакторная аутентификация (2FA), ограничение доступа для разных ролей.
2. **Валидация входных данных**:
- Валидация данных пользователя: Проверка корректности вводимых данных: имена, адреса, email, номера телефонов, даты.
- Проверка данных о платежах: Валидация данных, поступающих от платежных систем (номера кредитных карт, адреса доставки).
- Валидация данных заказов: Проверка корректности заказов (количество книг, цена, адрес доставки).

3. **Платежный модуль (Payment Gateway):** Этот модуль находится между контроллером приложения и внешним платежным шлюзом. Его задачи:
- Обработка платежей: Перевод данных о платеже в формат, понятный платежному шлюзу, и передача запроса на шлюз.
- Обработка ответов от шлюза: Прием и обработка ответа от шлюза. Обработка ошибок и возвращение соответствующего статуса контроллеру.
- Авторизация и аутентификация: Проверка подлинности платежа, использование токенов, хеширование, взаимодействие с системами аутентификации платежных шлюзов.
- Хранение данных о платежах (в зашифрованном виде): Сохранение истории транзакций в безопасной системе, изолированной от основных данных приложения.
- Обработка возвратов: Обработка и подтверждение возврата средств.

***
### Схема взаимодействия компонентов интернет-магазина (после кибериммунизации)
![изображение](https://github.com/kostya1962/Cyberimmunity/blob/main/%D0%A1%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%20%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%BC%D0%B0%D0%B3%D0%B0%D0%B7%D0%B8%D0%BD%D0%B0.drawio.svg)
***

## Заключение

Эта работа посвящена повышению безопасности книжного интернет-магазина “Я люблю читать!” Были выявлены ключевые угрозы безопасности, связанные с веб-сервисом, и внедрены некоторые меры по их уменьшению.

В ходе анализа предметной области были выделены ключевые ценности бизнеса, поставлены основные цели безопасности, которые включали защиту данных пользователей, предотвращащли мошенничество, обеспечивали целостность и доступность веб-ресурсов. Выявлены слабые места и возможные угрозы и определены сценарии, где эти угрозы могли бы реализоваться.

В результате построения и анализа архитектуры веб-ресурса были определены рекомендации по кибериммунизации, значительно повысившие безопасность интернет-магазина. Поддерживая высокий уровень безопасности, разрабатываемый интернет-магазин гарантирует его пользователям простые, надёжные и комфортные условия для совершения покупок книг онлайн. 

## Список использованных информационных источников

- [OWASP.ORG](https://cheatsheetseries.owasp.org/cheatsheets/Database_Security_Cheat_Sheet.html)
- [Правила безопасной эксплуатации сервера на PostgreSQL](https://www.postgresql.org/docs/current/runtime.html)
- [Model-View-Controller](https://ru.wikipedia.org/wiki/Model-View-Controller)
- [Платёжный шлюз](https://ru.wikipedia.org/wiki/%D0%9F%D0%BB%D0%B0%D1%82%D1%91%D0%B6%D0%BD%D1%8B%D0%B9_%D1%88%D0%BB%D1%8E%D0%B7)
- [БДУ ФСТЭК](https://bdu.fstec.ru/threat)
- [Калькулятор CVSS V2](https://bdu.fstec.ru/calc)
- [NGINX reverse proxy with ModSecurity WAF](https://github.com/carlosdg/NginxReverseProxyWithModsecurity)
- [Wapiti Key Features](https://www.kalilinux.in/2021/01/wapiti-tutorial.html)
- [Обзор OWASP ZAP. Сканер для поиска уязвимостей в веб-приложениях](https://habr.com/ru/companies/first/articles/709586/)
- [DoS- и DDoS-атаки](https://ru.wikipedia.org/wiki/DoS-%D0%B0%D1%82%D0%B0%D0%BA%D0%B0)


