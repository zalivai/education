### Запустить контейнеры
[docker-compose up](https://docs.docker.com/reference/cli/docker/compose/up/) - эта команда запускает контейнеры, праметр -d позволяет это делать в фоновом режиме (detached mode)

### Остановить контейнеры
[docker-compose down](https://docs.docker.com/reference/cli/docker/compose/down/) - эта команда остановит и удалит все контейнеры, созданные с помощью docker-compose up

### Посмотреть запущенные контейнеры
[docker-compose ps](https://docs.docker.com/reference/cli/docker/compose/ps/) - эта команда покажет список всех запущенных контейнеров и их статус

### Посмотреть логи контейнера
[docker-compose logs <service_name>](https://docs.docker.com/reference/cli/docker/compose/logs/) - с помощью этой команды можно посмотреть логи конкретного сервиса, например чтобы посмотреть логи сервиса postgres: docker-compose logs postgres