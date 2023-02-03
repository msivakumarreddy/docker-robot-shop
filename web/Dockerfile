FROM nginx
RUN rm -rf /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
RUN         rm -f /etc/nginx/conf.d/default.conf
ADD nginx.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/