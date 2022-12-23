FROM nginx:1.19-alpine AS server
COPY ./nginx.conf /etc/nginx/conf.d/default.conf
COPY . /usr/share/nginx/html