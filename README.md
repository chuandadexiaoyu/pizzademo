pizzademo
=========

A Laravel 4 demo app

This demo has been built on top of a modified version (extends) of [brunogaspar's L4 bootstrap app](https://github.com/brunogaspar), and is a simple demo project!


## Installation:
- Download laravel via ZIP, or run `git clone git@github.com:laravel/laravel.git .` in your project's dir
- check out the L4 branch: `git checkout develop`
- run `composer install`
- Download this "app" via ZIP somewhere and copy the contents into your project's folder (overwrite everything)
- then run `composer dump-autoload`
- create a database, e.g.: "pizza_web" (if you coose an other name, modify the config!)
- create the migrations table `php artisan migrate:install`
- and lastly seed the database: `php artisan migrate:refresh --seed`

## Features:
- Uses migrations
- Uses the brand new seeding feature
- Built with localizations in mind
- Validates forms with flashdata and response messages
- Has a few jQery filters
- Uses The built in authentication / authorization
- Controller based
- Uses database sessions

## Using the app:
You can log in with a test account:
```
email: test@test.com
password: test
```

Play with it! :)

(There is no registration currently since it wasn't necessary for my demo)