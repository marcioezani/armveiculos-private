# <p align="center"><b>ARM VEÍCULOS</b></p>

<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

Online shop for buying and selling vehicles

## Prerequisites

This tutorial assumes you have PHP and MySQL installed on your system. Follow the instructions for your operating system to install both of them.

You also need to be familiar with Linux/macOS bash where we'll be executing the commands in this tutorial.

Familiarly with PHP is required since Laravel is based on PHP.

For development I will be using a Ubuntu 20.04 machine so the commands in this tutorial are targeting this system but you should be able to follow this tutorial in any operating system you use.

# AMR VEÍCULOS

The Virtual Store for buying and selling vehicles has a page for viewing and selling vehicles and an administrative control panel for entering and selling vehicles.

## Installation

Clone the repository-
```
git clone ...
```

Then cd into the folder with this command-
``` 
cd armveiculos
```

Then do a composer install
```
composer install
```

Then create a environment file using this command-
```
cp .env.example .env
```

Then edit `.env` file with appropriate credential for your database server. Just edit these two parameter(`DB_USERNAME`, `DB_PASSWORD`).

Then create a database named `laravelcrud` and then do a database migration using this command
```
php artisan migrate --seed
```

## Run server

Run server using this command-
```
php artisan serve
```

Then go to `http://localhost:8000` from your browser and see the app.

## Screenshot

![](https://thumbs2.imgbox.com/d1/60/X2H4ra5j_t.png)
![](https://thumbs2.imgbox.com/e9/3c/Z1ChJs18_t.png)

## Credits

- [MEZ](https://github.com/marcioezani)
