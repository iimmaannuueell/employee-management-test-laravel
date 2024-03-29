# Employee Management 
[![Build Status](https://travis-ci.org/12march/employee-management-test.svg?branch=master)](https://travis-ci.org/12march/employee-management-test)

This help companies store and manage list of all their employee.

> This project will still be extended in the future. This is just complete the test requirement

## Prerequisite
- PHP 7
- Composer
- A database system

## Installation

### Step 1.
- Begin by cloning this repository to your machine 
```
git clone https://github.com/12march/employee-management-test-laravel.git
```

- Install dependencies
```
composer install
```

- Create enviromental file and variables
```
cp .env.example .env
```

- Generate app key
```
php artisan key:generate
```

### Step 2
- Next, create a new database and reference its name and username/password in the projects .env file. Below the database name is "emp_mngt"
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=emp_mngt
DB_USERNAME=root
DB_PASSWORD=
```

- Run migration
```
php artisan migrate
```

### Step 3
- To start the server, run the command below
```shell
$ php artisan serve
```

## Testin tools
- phpunit

### Testing directory
- AuthTest
- CompanyTest
- EmployeeTest


## Implemented Features
- Users can register on the application
- Users can login into the application
- Users can create a company
- Users can edit company detail
- Users can delete company 
- User sees only company they created on dashboard
- Company can add an employee
- Company can edit employees details
- Company can delete 


## Author
- Emmanuel Okeke
