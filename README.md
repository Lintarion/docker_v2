
## Домашнее задание к занятию «3.1. Docker» Задача №1 - PostgreSQL

### Шаги выполнения домашнего задания к Задаче №1:

1. Создать локальный репозиторий с файлами (gitignore, db-api.jar, application.properties, docker-compose.yml). Инициализировать его. Сделать commit. Привязать к удаленному репозиторию на GitHub. Сделать push
2. Запустить локально прдварительно установленный docker desktop. 
3. Запустить Intelege IDEA с предустановленным плагином Docker.
4. Скачать c ресурса https://hub.docker.com/_/postgres/tags: Image PostgreSQL (версия Image: 12-alpine)
5. В терминале Intelege IDEA набрать команду - docker pull postgres:12-alpine 
6. Вносим корректировки в файлы:
   - application.properties,
   - docker-compose.yml. 
7. Запускаем контейнер - docker-compose up
8. После того, как БД запустится, запустить целевое приложение: java -jar db-api.jar
9. Открыть в браузере адрес: http://localhost:9999/api/cards (при установленном расширении json viewer)
10. Результат работы представлен на скрине:

![Снимок экрана 2022-12-24 в 12 40 42](https://user-images.githubusercontent.com/110577193/209423147-5b7204ef-a094-4269-8d3b-1d406557de8b.png)
