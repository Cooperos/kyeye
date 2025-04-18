<p align="center"><img src="https://i.ibb.co/g4gTVHH/image.png" width="150" style=" border-radius: 50%;" alt="https://github.com/S0IG0/kyeye"></p>

# Проект информационной очереди
Этот проект представляет собой информационную очередь, основанную на Django для бэкенда и React для фронтенда и Nginx для http сервера. Весь проект может быть запущен при помощи команды `docker-compose up`.
### Установка и запуск
Для установки и запуска проекта необходимо выполнить следующие шаги:
1. Установить Docker, если они еще не установлены на вашем компьютере.
2. Склонировать репозиторий проекта на ваш компьютер `git clone https://github.com/Cooperos/kyeye.git`.
3. Открыть терминал и перейти в папку с проектом `cd kyeye`.
4. Выполнить команду `docker-compose up` для запуска контейнеров проекта.
5. После выполнения этих команд вы сможете открыть ваш браузер и перейти по адресу `http://localhost:80` для доступа к приложению.

### Структура проекта
```
queue/ 
├── backend/
│   ├── service/
│   ├── requirements.txt
│   └── Dockerfile
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── package-lock.json
│   └── Dockerfile
├── nginx/
│   ├── conf.d/
│   │   └── nginx.cong
│   └── loggs/
│       ├── access.log
│       └── errors.log
├── source/
│   ├── conf.py
│   └── index.rst
├── docker-compose.yml
├── env_file.env
└── README.md

```

* backend/ содержит файлы для запуска бэкенда Django.
* backend/service/ содержит приложения Django для проекта.
* backend/requirements.txt содержит зависимости Python для бэкенда.
* backend/Dockerfile содержит инструкции для сборки контейнера бэкенда.
* frontend/ содержит файлы для запуска фронтенда Vue.js.
* frontend/src/ содержит код Vue.js приложения.
* frontend/public/ содержит статические файлы фронтенда.
* frontend/package.json содержит зависимости для фронтенда.
* frontend/package-lock.json содержит заблокированные версии зависимостей для фронтенда.
* nginx/ содержит конфигурацию для Nginx и логи.
* nginx/conf.d/nginx.conf конфигурационный файл для Nginx.
* nginx/loggs/ содержит в себе два файла в которых будут записываться логи.
* source/ содержит файлы для настройки системы сборки документации.
* docker-compose.yml содержит инструкции для запуска всех контейнеров проекта.
* README.md содержит описание проекта.
### Архитектура проекта
![Архитектура проекта](https://i.ibb.co/qBT94Lp/Kyeye-project.png)

### Авторы
1. Бурнаев М.А.
2. Бондарь А.С.
3. Пиндюрин В.Д.
