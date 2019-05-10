FROM nginx

ADD 00-apps/budgety /etc/nginx/html
EXPOSE 80
ENTRYPOINT nginx -g
CMD ["daemon off"]
