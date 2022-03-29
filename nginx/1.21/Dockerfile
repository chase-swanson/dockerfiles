FROM nginxinc/nginx-unprivileged:1.21-alpine
USER root
RUN apk upgrade
RUN chown -R nginx /usr/share/nginx/html
USER nginx