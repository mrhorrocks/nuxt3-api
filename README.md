# nuxt3-api

[![](https://img.shields.io/badge/nuxt.js-v3.0.0-04C690.svg)](https://nuxt.com) [![](https://img.shields.io/badge/Laravel-v10.18.0-ff2e21.svg)](https://laravel.com) [![](https://img.shields.io/badge/php-v8.2.4-0000ff.svg)](https://www.php.net/) [![](https://img.shields.io/badge/node-v16.18.0-026e00.svg)](https://nodejs.org/en)

## Introduction

This repository is an implementation of the [Laravel Breeze](https://laravel.com/docs/starter-kits) application / authentication starter kit frontend in [Nuxt3](https://nuxt.com/). The authentication boilerplate is already written for you - powered by [Laravel Sanctum](https://laravel.com/docs/sanctum), allowing you to quickly begin pairing a Nuxt.js frontend with a powerful Laravel backend.

## OS Requirements

Install [Composer](https://getcomposer.org/), [Xampp](https://www.apachefriends.org/) & [Node.js](https://nodejs.org/en) onto your OS.

## Laravel API Installation

Start Mysql and create a new database.

Clone the repo locally:

```sh
git clone https://github.com/mrhorrocks/nuxt3-api.git
```

Change the terminal location to nuxt3-backend.

```sh
cd nuxt3-backend
```

Copy .env.example to .env:

```sh
cp .env.example .env
```

Generate application key:

```sh
php artisan key:generate
```

Open .env add the name of your database to DB_DATABASE=>*database-name-here*

Run database migrations

```sh
php artisan migrate
```

The api is now running on http://localhost:8000/

## Nuxt Installation  

Open another terminal in nuxt3-frontend and run

```sh
npm install && npm run dev
```

The nuxt app is now running on http://localhost:3000/

You can now navigate to http://localhost:3000/ and register a new account.

## Todo

* [ ] Connect the FRONTEND_URL in .env correctly in sanctum.php

