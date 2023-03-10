# Ping CRM React

A demo application to illustrate how [Inertia.js](https://inertiajs.com/) works with [Laravel](https://laravel.com/) and [React](https://reactjs.org/).

> This is a port of the original [Ping CRM](https://github.com/inertiajs/pingcrm) written in Laravel and Vue.

![](https://raw.githubusercontent.com/landish/pingcrm-react/master/screenshot.png)

## Requirements

```
PHP 8.1 or higher
Node ^14.18.0 || >=16.0.0
```

## Installation

Clone the repo locally:

```sh
git clone https://github.com/artemio87/pingcrm-react18-laravel10
cd pingcrm-react18-laravel10
```

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm install
```
Or

```sh
yarn install
```

Build assets:

```sh
npm run dev
```

Or

```sh
yarn dev
```

Setup configuration:

```sh
cp .env.example .env
```

Generate application key:

```sh
php artisan key:generate
```

Create an SQLite database. You can also use another database (MySQL, Postgres), simply update your configuration accordingly.

```sh
touch database/database.sqlite
```

Run database migrations:

```sh
php artisan migrate
```

Run database seeder:

```sh
php artisan db:seed
```

Run artisan server:

```sh
php artisan serve
```

You're ready to go! [Visit Ping CRM](http://127.0.0.1:8000/) in your browser, and login with:

- **Username:** johndoe@example.com
- **Password:** secret

** you need to make sure APP_URL on .env is setted like:
```code
APP_URL=http://127.0.0.1:8000
```

## Running tests

To run the Ping CRM tests, run:

```
phpunit
```

## Credits

- Original work by Jonathan Reinink (@reinink) and contributors
- Port to Ruby on Rails by Georg Ledermann (@ledermann)
- Port to React by Lado Lomidze (@landish)
- Upgrade to laravel 10 + inertia 1.0 + React 18 Artemio Rodriguez (@artemio87)
