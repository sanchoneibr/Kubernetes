FROM nginx

COPY ./nginx.conf /etc/nginx/nginx.conf

WORKDIR /etc/nginx/

EXPOSE 8000

CMD ["nginx", "-g", "daemon off;"]