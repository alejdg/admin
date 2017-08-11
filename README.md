# TrayLabs Admin

Admin dashboard for startups.

## Installation

You can install TrayLabs Admin using composer:

```ssh
$ composer create-project --prefer-dist tray-labs/admin /path/to/project
```

Or downloading a [zip file](https://github.com/tray-labs/admin/archive/master.zip).

Create the database for TrayLabsAdmin:
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

By default, the namespace's project is `TrayLabs\Admin`. You can change it manually if you feel so in the files below:

https://github.com/tray-labs/admin/blob/master/composer.json#L27

https://github.com/tray-labs/admin/blob/master/app/Http/Controllers/Auth/RegisterController.php#L5

https://github.com/tray-labs/admin/blob/master/config/auth.php#L70

https://github.com/tray-labs/admin/blob/master/config/services.php#L33

## License

This project is licensed under the MIT License.
