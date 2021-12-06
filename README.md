# home-server-nginx-proxy
Nginx proxy for my personal server

# Запуск через docker
Собрать образ
`docker build -t nginx-proxy .`

Запустить контейнер
`docker run -d --name nginx-proxy -p 80:80 nginx-proxy`