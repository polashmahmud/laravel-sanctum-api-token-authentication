# Laravel Sancum Api Token Authentication

<a href="https://github.com/polashmahmud/laravel-sanctum-api-token-authentication-client">Frontend Repositories</a>

<a href="https://www.youtube.com/watch?v=dfWEhh0mVYc&list=PLh-F6-XbduO_PidlrQWUTCW0PitcBRV8Q">YouTube Video tutorial link: Laravel Sanctum API Token Authentication</a>
<a href="https://www.youtube.com/watch?v=3hPYbGVqTto&list=PLh-F6-XbduO9fIFsspC9Gs9jdDiQVHFdx">YouTube Video tutorial link: Vue and Laravel Api Token Authentication</a>

## How to install

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
