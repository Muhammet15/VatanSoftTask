
composer i 
cp .env.example .env 
php artisan jwt:secret
php artisan migrate
php artisan storage:link
php artisan serve
php artisan test
...
