# pdl-wiremock-service

This repo will be used for mock services for both local development and testing.

docker run -it \
 --name wiremock-studio \
 -p 9000:9000 \
 -p 8080-8100:8080-8100 \
 -v $PWD:/home/wiremock \
 up9inc/wiremock-studio:2.32.0-18
