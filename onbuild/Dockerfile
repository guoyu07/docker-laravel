FROM thecontrolgroup/laravel:5.0

ONBUILD ADD composer.json /var/www/html
ONBUILD ADD composer.lock /var/www/html
ONBUILD ADD . /var/www/html

ONBUILD RUN composer install --prefer-dist && composer update
