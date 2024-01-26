# SfaxNews

SfaxNews is a simple web application built using Laravel and Vue 3, designed for creating posts and advertisements.

## How to Install

Follow these steps to set up the project on your local machine:

### Step 1: Install Dependencies

```bash
composer install
```

### Step 2: Copy Environment File

```bash
cp .env.example .env
```

### Step 3: Generate Application Key

```bash
php artisan key:generate
```

### Step 4: Run Migrations

```bash
php artisan migrate
```

### Step 5: Seed Database

```bash
php artisan db:seed
```

### Step 6: Install Node Modules

```bash
npm install
```

### Step 7: Import Database

Import the provided database into your phpMyAdmin. Database name: `databasemahdi`

### Step 8: Compile Assets

```bash
npm run dev
```

### Step 9: Start Laravel Development Server

```bash
php artisan serve
```

## Login Credentials

### Admin Login

- **Email:** admin@demo.com
- **Password:** 12345678

Feel free to explore and customize the application according to your needs!
