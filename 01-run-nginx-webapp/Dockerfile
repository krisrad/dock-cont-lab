FROM nginx

ADD 00-apps/budgety /etc/nginx/html
ADD 00-apps/budgety /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
