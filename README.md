

git clone https://github.com/suruzz123/stripe_laravel.git

https://dashboard.stripe.com/test/dashboard

## .env

STRIPE_KEY=

STRIPE_SECRET=

go to the cloned directory 

coposer update

See the stripe creadetials setup on config/services.php

set stripe creadetials on .env and also set the database credentials here

## also also set tripe creadetials on welcome.blade.php (line 58) 
var stripe = Stripe('give_your_stripe_here');

php artisan key:generate

php artisan migrate

php artisan serve








