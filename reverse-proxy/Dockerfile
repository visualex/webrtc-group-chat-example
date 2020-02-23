FROM nginx:alpine
COPY nginx.conf /etc/nginx/nginx.conf
RUN mkdir -p /www/data
COPY ssl/* /etc/nginx/
