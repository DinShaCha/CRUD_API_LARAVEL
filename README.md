Requirements
- Laravel
- Composer
- PHP
- Web Server
- Database
- Postman

- After downloading the project, please update the following in the .env file (located inside the crud_api folder) to match your database connection:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=crud_api
DB_USERNAME=root
DB_PASSWORD=

- Open the terminal in the project directory crud_api and run the following migration command to get the tables created:

php artisan migrate

- Once the above is complete, please run the following command on the terminal to run the server:

php artisan serve

- Finally, get the postman collection added to test the CRUD operations
