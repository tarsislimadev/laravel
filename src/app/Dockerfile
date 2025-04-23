FROM composer:lts

# RUN composer global require laravel/installer

WORKDIR /app

COPY . .

CMD php artisan serve --host=0.0.0.0 --port=80
