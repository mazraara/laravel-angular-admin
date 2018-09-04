# laravel-angular-admin

A simple admin panel using Angular and Laravel. Includes a user login, logout, register, forget password, book crud

To setup the front end follow below steps

```bash
npm install
```

```bash
ng serve
```

To change the API url and token in front end app, update the env variables at src/environment.ts , src/environment.prod.ts

To setup the back end follow below steps

Duplicate `.env.example` and rename it `.env`

Then run:

```bash
php artisan key:generate
```

```bash
php artisan migrate
```

```bash
php artisan jwt:generate
```

```bash
php artisan serve
```