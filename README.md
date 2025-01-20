<h1 align="center">Laravel</h1>

<p align="center">
    <a href="https://www.mysql.com/"><img src="https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"></a>
    <a href="https://www.php.net/"><img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white" alt="PHP"></a>
    <a href="https://laravel.com/"><img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel"></a>
    <a href="https://www.npmjs.com/"><img src="https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white" alt="NPM"></a>
</p>

## Database

```mysql
CREATE DATABASE `laravel` DEFAULT CHARACTER SET `utf8mb4` COLLATE `utf8mb4_general_ci`;
```

## Bootstrap

```shell
composer install
npm install && npm run build
cp .env.example .env
vim .env
php artisan key:generate
php artisan migrate
```

## Shortcuts

```shell
./vendor/bin/pint
```
