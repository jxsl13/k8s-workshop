FROM bitnami/php-fpm:8.0

RUN pear channel-discover pear.nrk.io
RUN pear install nrk/Predis

ADD guestbook.php /app/guestbook.php
ADD controllers.js /app/controllers.js
ADD index.html /app/index.html
