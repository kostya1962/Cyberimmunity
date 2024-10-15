# Отчёт о выполнении задания "Книжный интернет-магазин" по дисциплине "Основы безопасности кибериммунных систем"
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

Книжный интернет-магазин  "Я люблю читать!" — это веб-сервис для покупки книг в интернет-магазине. 

Основная цель магазина: предоставить пользователям удобный и безопасный способ приобретения книг, как в электронном, так и в физическом формате, с максимальной защитой персональных данных и финансовой информации.

Основные задачи интернет-магазина:
1. **Предоставление каталога книг**: магазин позволяет пользователям просматривать, фильтровать и искать книги по различным категориям, таким как жанр, автор, цена, новизна и т.д.
2. **Обеспечение управления пользователями**: создание личного кабинета для каждого пользователя, где можно управлять своими покупками, отслеживать историю заказов и сохранять книги в избранное.
3. **Оформление заказов и обработка платежей**: пользователи имеют возможность добавлять книги в корзину и оформлять заказы через простую и безопасную процедуру.
4. **Предотсавление возможности осуществления доставки**: магазин предлагает различные варианты доставки (для физических книг) и моментальный доступ к цифровым версиям книг (электронные и аудиокниги).
5. **Обратная связь и поддержка**: возможность оставить отзыв или оценку для каждой книги, что помогает другим покупателям принимать решение, а также интеграция службы поддержки, которая помогает пользователям решать вопросы, связанные с заказами, доставкой и техническими проблемами.
6. 

### Постановка задачи

Необходимо разработать архитектуру для web-приложения (далее ПО - программное обеспечение) для книжного интернет-магазина, задача которого: эффективно управлять каталогом книг, позволяя клиентам выбирать и покупать необходимые книги. Web-ресурс должен включать как десктопную, так и мобильную реализации, а также базу данных, хранящую персональные данные клиентов.

### Цели и Предположения Безопасности (ЦПБ)

В качестве целей безопасности можем выделить следующие пункты:
1. Обеспечить безопасность пероснальных данных клиентов, зарегестрировавшихся в web-сервисе, то есть не допустить их утечки.
2. Обеспечить защиту сервера базы данных на физическом уровне, то угроз физического взлома и DoS-атак.
3. Обеспечение безопасности процесса обработки информации платежа.

Предположения безопасности:
1. Дрон имеет защиту от атак на физическом уровне доступа.
2. Дрон имеет защиту от намеренного искажения GPS координат.
3. После получения задания дрон функционирует автономно и после выполнения задачи возвращается на базу кратчайшим маршрутом.

### Защищаемые ценности
| Ценность | Негативное событие | Оценка ущерба | Комментарии |Цели безопасности |
|----------|----------|----------| -------------- | ------- |
| Конфиденциальность персональных данных    |    |    |  | |
| Доступность интернет-ресурса    |    |    |  | |
| Целостность платёжной информации    |    |    |  | |
| Аутентификация аккаунта клиента |   |   |   | |
