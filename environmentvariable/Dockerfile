FROM nginx:mainline-alpine
RUN rm /etc/nginx/conf.d/*
ADD default.conf /etc/nginx/conf.d/
ADD index.html /usr/share/nginx/html/
ADD env.sh /usr/share/nginx/html/