# Laravel-Frequent-Commands

* [Create a Laravel Project][#Create-a-Laravel-Project]
* [Run the Development Server](#Run-the-Development-Server)
* [Generate a Model](#Generate-a-Model)
* [Generate a Migration](#Generate-a-Migration)
* [Run Migrations](#Run-Migrations)
* [Create a Controller](#Create-a-Controller)
* [Create a Resource Controller](#Create-a-Resource-Controller)
* [List All Available Routes](#ListAllAvailableRoutes)
* [list of all available Artisan commands](#list-of-all-commands)
* [Create a Request](#Create-a-Request)

## Create a Laravel Project
Creates a new Laravel project with the given name.
```sh
laravel new project-name
```
<hr>

## Run the Development Server
Starts the built-in development server for running the Laravel application.
```sh
php artisan serve
```
<hr>

## Generate a Model
Creates a new Eloquent model with the specified name.
```sh
php artisan make:model ModelName
```
<hr>

## Generate a Migration
Generates a new database migration file for creating a table
```sh
php artisan make:migration create_table_name
```
<hr>

## Run Migrations
Executes pending database migrations to create/update tables.
```sh
php artisan migrate
```
<hr>

## Create a Controller
Generates a new controller with the given name.
```sh
php artisan make:controller ControllerName
```
<hr>

## Create a Resource Controller
Creates a resourceful controller with CRUD methods.
```sh
php artisan make:controller --resource ControllerName
```
<hr>

## List All Available Routes
Displays a list of all registered routes in the application.
```sh
php artisan route:list
```
<hr>

## list of all available Artisan commands
To view a list of all available Artisan commands, you may use the list command:
```sh
php artisan list
```
<hr>

## Create a Request
Generates a new request with the given name
```sh
php artisan make:request RequestName
```