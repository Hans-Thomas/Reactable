# Reactable

## About Reactable

Reactable is a simple and easy to use project that lets you learning Reactive X faster.
this project's back-end implemented in laravel using Events and Broadcasts and also laravel-websockets package.
in front-end we used Vue js with axios for sending request and getting server response and show it using vue components.

- RxPHP commands with meaningful examples
- simple and fast
- SPA
- Progressive

## How to run
- first clone the repository and open a terminal in the root directory
- second enter `docker-compose up -d --build` (enter `--build` just for the first time)
- next `docker-compose app bash` and then `serice supervisor start` on every start up
- also `cp .env.example .env` and `php artisan key:generate` just once
- in the end run `php artisan migrate` and `chmod -R storage/ bootstrap/` just once too

## How to use
- to executing a method just need to type `run` before the method's name. for example if we have `foo` method
just change the name to `runfoo`.
- for showing up a message in result page, you can use `Output` class and `send` method.
- examples defined in three types (Loops, Observables and Operators). you can call each method statically.
- all the examples placed in `reactable/Examples` directory. feel free to insert a new method or manipulate methods.
