# test-passport-vue
test passport vue

## requirements
composer and node, this application uses laravel 5.5 so requirements for it also apply.

## installation
1. clone the repository
    git clone https://github.com/BeltranBot/test-passport-vue.git
2. install dependencies
    composer install
3. install npm dependencies
    npm install
4. compile npm assets
    npm run dev
5. create the database and set the configuration in the .env file
6. run the migrations
    php artisan migrate
7. set up passport tokens
    php artisan passport:install
 8. start artisan serve
    php artisan serve
 
 ## test it
 Once the application is up and running you have to go to the 'localhost:8000' address in you browser.
 You need to create an account in the top right corner to be logged in.
 After logged in you'll be send to the home page, that include among other things a button called 'fetch user data',
 after clicking it, it'll try to fetch the user credentials from the default '/api/user' and log them in the javascript console.
 
