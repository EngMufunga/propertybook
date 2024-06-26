# Corporate Website Laravel Application

This is a Laravel application. Follow the instructions below to get it up and running on your local machine.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [PHP] (>= 8.0).
- You have installed [Composer].
- You have installed [Git].
- You have installed [Node.js] and [npm].
- You have installed [Laravel].

## Cloning the Repository

1. Open your terminal or command prompt.
2. Navigate to the directory where you want to clone the repository.
3. Run the following command to clone the repository:

git clone https://github.com/EngMufunga/propertybook.git

cd your-repository

Run composer install

Copy the example environment file and create a new one

Run php artisan key:generate

Configure your environment variables in the .env file. Update the following lines with your database information:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password

Run The following commands
- php artisan migrate
- npm install
- npm run dev
- php artisan serve


Access the application on the following urls

Admin panel - http://127.0.0.1:8000/dashboard
Frontend - http://127.0.0.1:8000

