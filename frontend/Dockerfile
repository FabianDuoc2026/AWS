
FROM nginx:1.19.0-alpine


COPY default.conf /etc/nginx/conf.d/default.conf

COPY index.html /usr/share/nginx/html/
COPY app.js /usr/share/nginx/html/


EXPOSE 80