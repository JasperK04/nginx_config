FROM nginx:alpine

COPY ./sites /etc/nginx/conf.d
COPY ./config/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
