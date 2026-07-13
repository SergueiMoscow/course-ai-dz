В связи с ограничением tiral Dumplingai.com в 3 дня

![img](img/00-dumplingai-restrictions.png)

Было принято решение использовать другой сервис для поиска телефонов в Google, а именно, [SerpAPI](https://serpapi.com), который даёт 250 бесплатных ежемесячных запросов.

Для использования этого API принял решение навайбкодить и развернуть [собственный API](https://github.com/SergueiMoscow/phone-search-api), который использовал для выполнения настоящего ДЗ.

Свой API временно развернул на [домашнем сервере](https://search.sushkovs.ru/search)

## Определение переменных для запроса
![img](img/01-variables.png)

## API отработал и выдал результат
![img](img/02-request.png)

Т.к. в коде уже встроен механизм отбора номеров телефонов из snippet, модуль Text Parser опускаем.

## Фильтр по наличию номера телефона
![img](img/03-filter.png)

## Запись в Google Sheet
![img](img/04-add-row.png)

## Результат в таблице
![img](img/05-result-in-sheet.png)