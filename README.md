# SundaySim
A CMS build upon Laravel

This repository contains the completed project for this course—a simple content management system.

The source for this application is mainly located within the app directory. Within here we have various directories each responsible for a particular piece of the application.

To get a local copy of the application working you can follow the instructions below (assuming you're on a *nix machine):

run the following commands from your terminal:

$ composer install
$ php artisan migrate
$ php artisan db:seed
$ npm install
$ gulp
If you'd like to use Artisan to serve your application you can run the following command:

$ php artisan serve
This will then serve the application to localhost:8000.

Otherwise use Homestead to serve the application.
