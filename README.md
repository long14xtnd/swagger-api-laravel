1. composer require "darkaonline/l5-swagger"
2. open your config/app.php and add this line: L5Swagger\L5SwaggerServiceProvider::class
3. php artisan vendor:publish --provider "L5Swagger\L5SwaggerServiceProvider"
4. Connect Database.
5. Run php artisan migrate:fresh --seed
6. php artisan l5-swagger:generate

https://www.youtube.com/watch?v=p3Z3RR091Wk
