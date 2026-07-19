FROM docker.io/nginxinc/nginx-unprivileged:1.28-alpine

COPY --chown=101:101 index.html /usr/share/nginx/html/index.html
COPY --chown=101:101 app.js /usr/share/nginx/html/app.js
COPY --chown=101:101 styles.css /usr/share/nginx/html/styles.css

EXPOSE 8080
