# Базовый образ
FROM nginx:alpine

# Устанавливаем curl для проверки API-запросов из контейнера
RUN apk add --no-cache curl

# Копируем нашу страницу в дефолтную директорию Nginx
COPY index.html /usr/share/nginx/html/index.html