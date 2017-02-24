FROM nginx
COPY ./webapp /usr/share/nginx/html
COPY nginx-config.conf /etc/nginx/nginx.conf

RUN chmod -R g+rw /var
RUN chgrp -R 0 /var

