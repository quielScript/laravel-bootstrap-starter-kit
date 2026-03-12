# Laravel Starter Kit

A simple Laravel starter template designed for quickly starting new Laravel projects with a minimal setup.

This starter kit includes a clean Laravel installation with SQLite and Pest configured, allowing developers to start building immediately.

---

## Tech Stack

- Laravel
- Bootstrap Styles
- SQLite database
- Pest testing framework
- Vite for frontend assets

---

## Requirements

Before using this starter kit, make sure you have the following installed:

- PHP 8.2+
- Composer
- Node.js and npm
- Git

You can check installed versions with:

```js
php - v;
composer - v;
node - v;
npm - v;
```

---

## Creating a New Project From This Starter Kit

Clone the repository and rename the project folder:

```js
git clone https://github.com/your-username/laravel-bootstrap-starter-kit.git my-project
```

Navigate into the project directory:

```js
cd my-project
```

Remove the original git history:

Powershell:
```js
Remove-Item -Recurse -Force .git
```

Linux / macOS (Bash / Zsh):
```js
rm -rf .git
```

Windows CMD (Command Prompt):
```js
rmdir /s /q .git
```

Initialize a new git repository:

```js
git init
git add .
git commit -m "Initial commit"
```

(Optional) Connect to your own GitHub repository:

```js
git remote add origin https://github.com/your-username/my-project.git
git push -u origin main
```

---

## Install Dependencies

Install PHP dependencies:

```js
composer install
```

Install frontend dependencies:

```js
npm install
```

---

## Environment Setup

Create your environment file:

```js
cp.env.example.env;
```

Generate the Laravel application key:

```js
php artisan key:generate
```

---

## Run Database Migrations

Run the migrations to create the database tables:

```js
php artisan migrate
```

---

## Running the Application

Start the Laravel development server:

```js
php artisan serve
```

Start the Vite development server:

```js
npm run dev
```

The application will be available at:

`http://127.0.0.1:8000`

---

## Running Tests

This project uses **Pest** for testing.

Run tests with:

```js
php artisan test
```

or

```js
./vendor/bin/pest
```

---

## Project Structure Overview

`app/`
Contains application logic (controllers, models, services)

`routes/`  
Defines application routes

`resources/views/`  
Blade templates

`database/`  
Database migrations, seeders, and SQLite database

`tests/`  
Pest test files

---

## Purpose of This Starter Kit

This repository exists to speed up Laravel project creation by providing a minimal, ready-to-use setup.

Instead of configuring Laravel from scratch each time, you can start development immediately.

---

## License

This project is open-source and available under the MIT license.
