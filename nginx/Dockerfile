FROM nginx

COPY nginx.conf /etc/nginx/nginx.conf

RUN mkdir /etc/nginx/ssl

COPY ./ssl/server.crt /etc/nginx/ssl/
COPY ./ssl/server.key /etc/nginx/ssl/
