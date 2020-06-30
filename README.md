## production create react app with docker and nginx

`docker build --tag cra-docker-prod-image:1 .`

`docker run --name cra-docker-prod-container -p 3003:3000 cra-docker-prod-image:1`
