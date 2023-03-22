### Commands

#### To remove containers and images for this project
```
docker container stop urlshortener-api-1 urlshortener-db-1 urlshortener-frontend-1
docker rm urlshortener-api-1 urlshortener-db-1 urlshortener-frontend-1
docker rmi urlshortener-api urlshortener-db urlshortener-frontend
```

#### To run docker compose in detached mode
```
sudo docker compose up -d
```

#### To install required packages
```
cd api
go mod tidy
cd ..
```