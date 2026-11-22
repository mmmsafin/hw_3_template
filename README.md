запуск: copy .env.example в .env, потом docker compose up -d --build --wait
настройки в .env: greeting (приветствие) и host_port (порт на компьютере, по умолчанию 8080)
проверка: curl.exe http://127.0.0.1:8080/ и curl.exe -X POST http://127.0.0.1:8080/increment
отчет в report.md
