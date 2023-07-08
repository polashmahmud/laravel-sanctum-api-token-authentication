# Laravel Sancum Api Token Authentication

## How to install (Backend)

```
mkdir laravel-sanctum-api-token-authentication
```

```
cd laravel-sanctum-api-token-authentication
```

```
git clone git@github.com:polashmahmud/laravel-sanctum-api-token-authentication.git api
```

```
cd api
```

```
composer install
```

```
cp .env.example .env
```

<p>Update env db connection</p>

```php
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

<p>Update env mail information</p>

```php
MAIL_MAILER=smtp
MAIL_HOST=mailpit
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"
```
<p>Run Server</p>

```php
php artisan serve
```
<p>Run queue</p>

```php
php artisan queue:word
```
