# API Carros

This project was built with Lumen Framework

## Step 01

```
git clone ...
```

## Step 02

Create your database with Sqlite or other

## Step 03

Copy `.env` file

```cp .env.example .env```

## Step 04

Configure your database with your credentials. After configure the `.env` file and run this:

```
sudo docker-compose build app
sudo docker-compose up -d
sudo docker-compose ps
sudo docker-compose exec app composer install
docker-compose exec app php artisan migrate
```

## Endpoints

Where `BASE_URL` is `http://localhost:8383` for example

 - **GET** *{BASE_URL}*/api/carro
 - **GET** *{BASE_URL}*/api/carro/1
 - **POST** *{BASE_URL}*/api/carro
 - **PUT** *{BASE_URL}*/api/carro/1
 - **DELETE** *{BASE_URL}*/api/carro/1
