# Интеграция с GREEN-API

Этот проект демонстрирует, как использовать API GREEN-API для отправки сообщений и работы с настройками инстанса.

## Логика работы программы

1. Пользователь заходит на страницу и вводит параметры подключения:
   - **idInstance** — идентификатор инстанса.
   - **ApiTokenInstance** — токен для доступа к инстансу.
   
2. После ввода данных пользователь может нажимать на кнопки:
   - **Получить настройки** — вызов метода `getSettings`.
   - **Получить состояние инстанса** — вызов метода `getStateInstance`.
   - **Отправить сообщение** — вызов метода `sendMessage`.
   - **Отправить файл по URL** — вызов метода `sendFileByUrl`.
   
3. Ответы от API будут отображаться в поле ниже кнопок.

## Необходимое окружение

Для работы потребуется:
- Рабочий инстанс GREEN-API (создать на [green-api.com](https://green-api.com)).
- Совместимый веб-браузер.

## Установка

1. Клонируйте репозиторий:
git clone https://github.com/yourusername/green-api-integration.git
2. Откройте файл `index.html` в браузере.

## Важные замечания

- Для отправки сообщений и файлов нужно заменить `номер_телефона` и `fileUrl` на реальные данные.


## README на английском

# GREEN-API Integration

This project demonstrates how to use the GREEN-API to send messages and interact with instance settings.

## Program Logic

1. The user enters the connection parameters:
   - **idInstance** — instance ID.
   - **ApiTokenInstance** — access token for the instance.
   
2. After entering the data, the user can click on the buttons:
   - **Get Settings** — calls the `getSettings` method.
   - **Get State of Instance** — calls the `getStateInstance` method.
   - **Send Message** — calls the `sendMessage` method.
   - **Send File by URL** — calls the `sendFileByUrl` method.
   
3. Responses from the API will be displayed in the box below the buttons.

## Required Environment

To run the project you will need:
- A working GREEN-API instance (create one at [green-api.com](https://green-api.com)).
- A compatible web browser.

## Installation

1. Clone the repository:
git clone https://github.com/yourusername/green-api-integration.git
2. Open the `index.html` file in your browser.

## Important Notes

- To send messages and files, you need to replace `phone_number` and `fileUrl` with real data.

