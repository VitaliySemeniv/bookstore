FROM nginx:alpine

# Копіюємо файл
COPY ./templates/index.html /usr/share/nginx/html/index.html

# Встановлюємо правильні права доступу
RUN chmod 644 /usr/share/nginx/html/index.html
