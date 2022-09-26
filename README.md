# Personal-Website

## How to deploy it with Docker

```
docker build -t my-website .
docker run -it -d -p 80:80 my-website
```

## How to deploy it from Azure repository

```
az acr build --registry mypersonalwebsiteregistry --image webimage .
```