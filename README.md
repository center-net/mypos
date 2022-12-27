# mypos

composer install

cp .env.example .env

php artisan key:generate

php artisan migrate:fresh --seed

# rm -rf composer.lock
# rm -rf vendor
# composer install
