How to Install Laravel 12 on Windows (Quick Guide)

Laravel 12 is now officially released! Follow these simple steps to install Laravel 12 on Windows.

1️⃣ Install XAMPP or WAMP

Ensure PHP version 8.2 or higher.

🔹 Download XAMPP: https://www.apachefriends.org/download.html

🔹 Download WAMP: http://www.wampserver.com/en/

Start Apache and MySQL after installation.

2️⃣ Install Composer

🔹 Download Composer: https://getcomposer.org/download/

Install it and verify with:

composer

3️⃣ Install Laravel 12

Via Composer Create-Project

composer create-project --prefer-dist laravel/laravel my-laravel-app

Via Laravel Installer

composer global require laravel/installer
laravel new my-laravel-app

For Laravel 12 explicitly:

composer create-project --prefer-dist laravel/laravel project_name "12.*"

4️⃣ Run Laravel 12

cd my-laravel-app
php artisan serve

👉 Open http://127.0.0.1:8000/

5️⃣ Check Laravel Version

php artisan --version

✅ It should display Laravel Framework 12.0.0

For common issues and troubleshooting, watch the full tutorial:📺 Complete Instructions: https://www.youtube.com/watch?v=_htRdjlPnzk

🚀 Subscribe for more Laravel tutorials!
Youtube.com/StackDevelopers
