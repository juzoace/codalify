Exam by [Your full name], [date], [time started], [time ended]

## Exam by

## Name
Nwigwe Uzochukwu 

## Date Started 
9/16/2023

## Date Ended
9/19/2023

## About the app

The app has two folders, front-end and Back-end. The front-end is built with Vue.js while the backend is built with laravel (php). The database used is mysql

## Running the app
## Frontend
1. First you need to move into the frontend directory and install dependencies using: npm install 

2. To run the app simple use the command: 'npm run serve'


## Backend
To run the backend app ensure you have your MySQL database running on port 3306.

Check the sample.env file and ensure that you you fill in the necessary data.

Example:

APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:T/doGvFqKYV2graVg0uX4kfc0Nuln2ZJ2dwjlPqkw1U=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=youtube_db
DB_USERNAME=root
DB_PASSWORD=********

1. You need to move into the backend directory and install project dependencies using: composer install


2. There are already migration files provided so you just need to run this command: php artisan migrate


3. After run this command to start the app: php artisan serve

