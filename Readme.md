### Project Setup
1. Clone repository
2. cd into project root and run command [composer install]
3. create mysql database eg blog
4. copy .env.example and rename .env
4. update database credentials in .env
5. npm install
6. run command [php artisan key:generate]
7. run command [php artisan jwt:secret]
8. run command [php artisan migrate]
9. run command [php artisan db:seed]
10. serve app with command [php artisan serve]

### Admin User
1. default admin email [admin@medium.com]
2. default admin password [password] 

### Run Test
1. copy .env.example to .env.testing
2. create test mysql db eg blog-test
3. update .env.testing db credentials
4. run command [composer test]
