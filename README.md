# Real-Time Apps

A real-time apps built with Laravel Echo and Pusher.

## Getting started

### Prerequisites
```bash
php -v
composer -V
mysql -V
```

### Installing

Clone this repo.

```bash
git clone https://github.com/sc27kr/laravel-realtime-apps.git
```

Copy .env.

```bash
cd laravel-realtime-apps
cp .env.example .env
```

Install the project dependencies.

```bash
composer i
npm i
```

Create database and migrate.

```bash
mysql -uroot -p -e "CREATE DATABASE laravel"
php artisan migrate
```

Set the applicatioin key.

```bash
php artisan key:generate
```

Serve the application on the PHP development server.

```
npm run dev
php artisan serve
```

List all registered routes.

```bash
php artisan route:list
```

Enjoy! [localhost:8000](http://localhost:8000)

## Built with

* PHP
* Laravel
* Laravel Echo
* Pusher
