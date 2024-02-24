# Инструмент работы с кошельками

## Установка
`npm install` 

Заполняем файлы адресами в папке `addresses`

Для запуска `npm start`

## Что умеет

### Веб сервер

Запускает локальный сайт, с помощью которого можно смотреть всю описанную ниже статистику в браузере. Есть сортировка колонок, подсвечивание низких балансов и т.д.  

### Проверка активности

### Чекер сетей:
* ZkSync
* Starknet
* Layerzero
* Zora
* Aptos
* Linea

Покажет в консоли и сохранит в csv файл следующую инфу:
* Баланс в эфире/стейблах
* Количество транзакций
* Уникальные дни/недели/месяцы
* Первая и последняя транзакции
* Количество потраченного газа
* Специфичную для чейна инфу

### Получение балансов

Покажет баланс нативного токена/usdt/usdc/dai в выбранной сети. Доступны: eth, arbitrum, optimism, polygon, bsc, avalanche.

### EVM Checker

* Количество транзакций
* Уникальные дни/недели/месяцы
* Первая и последняя транзакции
* Количество потраченного газа

Этот скрипт рекомендую именно клонировать, а не качать zip - так как это будет универсальный скрипт для работы с кошельками, и со временем туда переедет функционал проверки балансов по EVM сетям.

Для работы с EVM Checker нужно переименовать .env.example в .env и добавить Moralis API Key
