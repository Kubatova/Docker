# Docker

Инструкции по запуску и тестированию приложения

Склонируйте репозиторий.
В каталоге с проектом выполните docker-compose up -d и docker-compose build nginx для запуска всех сервисов.
Откройте браузер и перейдите по адресу http://localhost:80 для доступа к веб-приложению через Nginx.

Тестирование PHP скрипта
Зайдите в контейнер Apache: docker exec -it apache-container bash.
Внутри контейнера выполните php test.php.
Проверьте, что вывод содержит "Connected successfully to MySQL!".

Дополнительные шаги
Для остановки контейнеров выполните docker-compose down
