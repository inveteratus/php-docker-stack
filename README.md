# PHP-Docker-Stack

A simple docker stack for PHP with MySQL, Redis, Nginx and Adminer.

# Installation

~~~sh
mkdir <app>
cd <app>

git clone https://github.com/inveteratus/php-docker-stack.git .
cp env.example .env
composer install
~~~

Now edit .env to suit.

**APP_NAME** needs to be a single word or kebab-case name.

