FROM nginx

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/conf.d/nginx.conf
COPY ssl.pem /etc/nginx/ssl.pem
COPY ssl.key /etc/nginx/ssl.key

CMD ["nginx", "-g", "daemon off;"]