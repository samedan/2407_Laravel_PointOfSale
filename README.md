> composer create-project laravel/laravel blog-app
> composer require tymon/jwt-auth

### DBB

# User Model

> php artisan migrate

# Edit UserFactory, DatabaseSeeder

> php artisan db:seed

### JWT-Auth

> https://jwt-auth.readthedocs.io/en/develop/laravel-installation/

# Token expire time

> .env -> JWT_TTL=1440
