# Laravel Vue.js TodoList App

This is a Web Application leveraging on Vue.js and Laravel to create SPA(Single Page Application) application.

The following must be installed and available on your terminal:
- [x] [composer]
- [x] [npm]
- [x] [php]
- [x] [mysql]


### INSTALLATION GUIDE
1. Clone the project
1. ``cd`` to the project and run ``composer install`` on the terminal to install php dependencies
1. Create a Mysql database and edit the ``.env`` to reflect your connections as follows:
    ```dotenv
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=dbname
    DB_USERNAME=myuser
    DB_PASSWORD=mypass
    ```
1. Migrate your migrations: `php artisan migrate`
1. Generate application encryption key: `php artisan key:generate`
1. Run `npm install && npm run dev` to install node.js dependencies
1. Start your development server and start testing the web app. `php artisan serve --port 8080`
