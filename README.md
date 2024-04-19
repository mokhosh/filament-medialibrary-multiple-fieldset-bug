# Reproduction Repo

1. `git clone git@github.com:mokhosh/filament-medialibrary-multiple-fieldset-bug.git`
2. `cd filament-medialibrary-multiple-fieldset-bug`
3. `composer install`
4. `php artisan migrate:fresh --seed`
5. `php artisan key:generate`
6. `php artisan serve`
7. Go to users resource and see fields not working.
8. Comment out `UserResource:41` and see things working again.
