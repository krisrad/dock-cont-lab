FROM nginx

ADD 00-apps/budgety /usr/share/nginx/html/budgety
ADD 00-apps/kitten_web /usr/share/nginx/html/kitten_web
ADD 00-apps/todolist /usr/share/nginx/html/todolist
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
