## Build
docker build -t ajegu-php php/   
docker build -t ajegu-php-fpm php-fpm/   
docker build -t ajegu-nginx nginx/   

## Tag
docker tag ajegu-php:latest ajegu/php:latest   
docker tag ajegu-php-fpm:latest ajegu/php-fpm:latest   
docker tag ajegu-nginx:latest ajegu/nginx:latest   

## Publish
docker push ajegu/php:latest   
docker push ajegu/php-fpm:latest   
docker push ajegu/nginx:latest   