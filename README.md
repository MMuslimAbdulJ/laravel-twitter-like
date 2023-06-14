# Just _iseng_ practice

### How to run the project step by step

-   Clone Repository

```
 git clone https://github.com/MMuslimAbdulJ/laravel-twitter-like.git
```

-   Go to the project

```
cd laravel-twitter-like
```

-   Make and edit your .env :

    -   Make some change and add some variable or add the value to like below, but if the variable already exist just change the value:
        -   DB_CONNECTION=sqlite
        -   APP_TIMEZONE='Asia/Jakarta'
        -   MAIL_MAILER=log (you can open the example email in logging at `storage/logs/laravel.log`)
    -   but run it first before edit the .env:

    ```
    cp .env.example .env
    ```

-   run generate key

```
php artisan key:generate
```

-   Install dependencies

```
composer install
```

-   Run migrations

```
php artisan migrate
```

- Run npm
~~~
npm run dev
~~~


-   Finally run

```
php artisan serve
```
