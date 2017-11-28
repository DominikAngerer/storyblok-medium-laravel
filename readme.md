# Storyblok Laravel Starter

![Storyblok Laravel](https://cdn-images-1.medium.com/max/2000/1*XtAABo6IRrewPMkvon1AiA.png)

Following the tutorial on [Medium](https://medium.com/p/d92a6316bbf8 ) or in the [Storyblok Stories](https://www.storyblok.com/stories) will result in this setup.

## How to install laravel

Follow [their installation guide](https://laravel.com/docs/5.5/installation#installing-laravel) - but basically it is:

```
# Install Laravel with Composer
composer global require "laravel/installer"
```

## Start this project

Follow the tutorial mentioned above to setup your Storyblok space and 
create exactly this source code or [click this link](https://app.storyblok.com/#!/build/41833) which will
create your space if you're logged in.

Or simply clone this repository and change the `accesToken` in `routes/web.php` to the privateToken of your
Storyblok space - After that execute:

```
composer install && php artisan serve
```

### Laravel Requirements:

- PHP >= 7.0.0
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension