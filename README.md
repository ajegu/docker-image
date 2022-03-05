## Build
docker build -t allcoin-php php/
docker build -t allcoin-nginx nginx/

## Tag
docker tag allcoin-php:latest ajegu/php:latest
docker tag allcoin-nginx:latest ajegu/nginx:latest

## Publish
docker push ajegu/php:latest
docker push ajegu/nginx:latest