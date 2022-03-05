## Build
docker build -t ajegu-php php/   
docker build -t ajegu-nginx nginx/   

## Tag
docker tag ajegu-php:latest ajegu/php:latest   
docker tag ajegu-nginx:latest ajegu/nginx:latest   

## Publish
docker push ajegu/php:latest   
docker push ajegu/nginx:latest   