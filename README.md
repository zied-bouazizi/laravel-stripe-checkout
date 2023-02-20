# laravel-stripe-checkout

Stripe online payments checkout process with Laravel 9

## Usage

### Install Dependency
```
composer install
```

### Database Setup
Change the `.env.example` to `.env` and add your database info

For SQLite, add
```
DB_CONNECTION=sqlite
```

Create a `database.sqlitefile` in the `database` directory

### Migrations
To create all the nessesary tables and columns, run the following
```
php artisan migrate
```

### Seeding The Database
To add dummy data, run the following
```
php artisan db:seed
```

### Run the webserver on port 8000
```
php artisan serve
```
