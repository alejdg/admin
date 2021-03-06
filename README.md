# TrayLabs Admin

Admin dashboard for startups.

## Installation

You must install TrayLabs Admin by composer:

```ssh
$ composer create-project --prefer-dist tray-labs/admin /path/to/project
```

Or download a [zip file](https://github.com/tray-labs/admin/archive/master.zip).

Create a database for TrayLabsAdmin:
```sql
CREATE DATABASE admin;
```

Setup .env file for database access.

Install dependencies from php:

```ssh
$ composer install

```

Install dependencies from javascript:

```ssh
$ yarn

```

Run npm to compile:
```ssh
$ npm run dev
```

Run migrations:
```ssh
$ php artisan migrate
```

## Configuration

By default, the namespace's project is `TrayLabs\Admin`.
If you want, you can change manually the namespace:

https://github.com/tray-labs/admin/blob/master/composer.json#L27
https://github.com/tray-labs/admin/blob/master/app/Http/Controllers/Auth/RegisterController.php#L5
https://github.com/tray-labs/admin/blob/master/config/auth.php#L70
https://github.com/tray-labs/admin/blob/master/config/services.php#L33

## License

This project is licensed under the MIT License.