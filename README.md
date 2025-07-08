## Guide

docker pull your-image-name

## Create a Dockerfile that copies your custom default.conf

## Dockerfile
FROM your-image-name

COPY default.conf /etc/nginx/conf.d/default.conf
## Dockerfile end

docker build -t tgigameshop-sg-5 .

docker tag tgigameshop-sg-5 yeminthandev/tgigameshop-sg-5
docker push yeminthandev/tgigameshop-sg-5