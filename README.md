# API Carros

This project was built with Lumen Framework

## Step 01

```
git clone ...
composer install
```

## Step 02

Copy `.env` file

```cp .env.example .env```

## Step 03

Configure your database with your credentials. After configure run this:

```
php7.4 artisan migrate
```

## Endpoints

Where `BASE_URL` is `http://localhost:8181` for example

 - **GET** *{BASE_URL}*/api/carro
 - **GET** *{BASE_URL}*/api/carro/1
 - **POST** *{BASE_URL}*/api/carro
 - **PUT** *{BASE_URL}*/api/carro/1
 - **DELETE** *{BASE_URL}*/api/carro/1
