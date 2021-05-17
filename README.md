Install composer. 

Clone repo
cd into your project
Install Composer Dependencies `composer install`
Install NPM Dependencies `npm install`
Create a copy of your .env file `cp .env.example .env`
Generate an app encryption key `php artisan key:generate`
Create an empty database for our application
Migrate Database `php artisan migrate`
Run `php artisan passport:install`

Start the development server `php artisan serve`

Test api with the following url: 

`localhost:800/0api/register` sending name, email, password and password_confirmation keys on body

`localhost:8000/api/login` sending email and password.




