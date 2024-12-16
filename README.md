#### E-commerce application built with Laravel, Vue.js, Tailwind.css and Inertia.js with Stripe Payment

#### installation

Make sure you have environment setup properly. You will need MySQL, PHP8.1, Node.js and composer.

#### Install Laravel Website + API

1. Download the project (or clone using GIT)
2. Copy .env.example into .env and configure database credentials
3. Navigate to the project's root directory using terminal
4. Run `composer install`
5. Set the encryption key by executing `php artisan key:generate`
6. Run migrations `php artisan migrate --seed`
7. Run data seeder to test ` php artisan db:seed AdminSeeder` and and other db seeder files you can find under database/seeders
8. Start local server by executing `php artisan serve`
9. Open new terminal and navigate to the project root directory
   Run `npm install`
10. Run `npm run dev` to start vite server for Laravel frontend
11. For Stripe Api key, please go to .env file and replace with your api key for this variable `STRIPE_KEY="REPLACE WITH YOUR STRIP API KEY HERE"`

git remote add origin https://github.com/fake985me/twe.git
git branch -M main
git push -u origin main
