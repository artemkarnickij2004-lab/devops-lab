# 01-linux

## systemd-юнит hello
Статический сервер на :8080.
- Unit: /etc/systemd/system/hello.service
- Проверка: systemctl status hello
- Перезапуск при падении: Restart=on-failure

