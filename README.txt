Запуск контейнера с RabbitMQ
- из папки docker запустить docker-compose up -d

Запуск приложения NestJs
- из папки nestjs-socket-microservice запустить npm i npm
- из папки nestjs-socket-microservice запустить npm run start:dev

Тестирование:
- В файле ws-client.py поменять значение переменной client_count. Это количество socket соединений к микросервису
- В файле send-message-to-rabbitmq.py поменять значение message_count - это количество отправляемых сообщений в rabbitMQ
- Запустить скрипт ws-client.py Это создаст соединения.
- Запустить скприпт send-message-to-rabbitmq.py - это отправит сообщения в брокер
- В терминале запуска ws-client.py будет отображаться ход получения сообщений
