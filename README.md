# websocket-node
# Пример скрипта для передачи сообщения через WebSocket

Пример простого скрипта, который передает сообщения с клиентской части (HTML) на серверную часть (ws://localhost:8080) , server.js, же создает саму серверную часть WebSocket, и получает с серверной части, сообщения полученное с клиентской части.

## Инструкции по установке и запуску

1. **Установите зависимости**:
npm install ws, node server.js

Сервер будет запущен на порту 8080.

3. **Откройте веб-страницу**:
Откройте веб-браузер и перейдите по адресу `http://localhost:8080`.

4. **Отправляйте сообщения**:
Введите сообщение в поле ввода на веб-странице и нажмите кнопку "Отправить". Сообщение будет отправлено на сервер, который выведет его в консоль и отправит обратное сообщение на веб-страницу.

## Структура скрипта

- `index.html`: Клиентская веб-страница, содержащая поле ввода и кнопку "Отправить".
- `server.js`: Серверная часть приложения, создающая WebSocket-сервер и обрабатывающая полученные сообщения.

## Зависимости

- `ws`: Версия 8.3.0 или выше. Используется для создания WebSocket-сервера в Node.js

