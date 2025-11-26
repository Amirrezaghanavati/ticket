# Ticket Management System

A Laravel-based ticket management system that follows Laravel's standard MVC architecture with additional service classes for business logic separation.

## Installation

### Clone the repository

```bash
git clone https://github.com/Amirrezaghanavati/ticket.git
cd ticket
```

### Install PHP dependencies

```bash
composer install
```

### Copy and configure environment file

```bash
cp .env.example .env
```

Update database credentials and other environment variables in `.env`.

### Generate application key

```bash
php artisan key:generate
```

### Run database migrations and seed default data

```bash
php artisan migrate --seed
```

### Default Admin Credentials

After seeding, you can log in with the following admin accounts:

-   **Admin 1**: `admin1@ticket.com` / `password`
-   **Admin 2**: `admin2@ticket.com` / `password`

### Build front-end assets (Optional)

```bash
npm install
npm run build   # or npm run dev
```

### Start local development server

```bash
php artisan serve
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
