# Cron Job with Laravel

## Description

This project was built for an authomatic email to all users on the platform. It authomatically sends emails to all users at a particular period

## Prerequiste

<ul>
    <li>PHP 7</li>
    <li>Composer</li>
    <li>MySQL</li>
</ul>

## Technologies used

Modern PHP technologies were adopted for this project

Laravel: Laravel is a web application framework with expressive, elegant syntax. We’ve already laid the foundation — freeing you to create without sweating the small things.
Visit [here](https://laravel.com/) for more information.


Mysql - Relational Database System used in project.

Gmail - Email SMTP client that enable you to send emails.

## Installation

### Step 1.
- Begin by cloning this repository to your machine 
```
git clone https://github.com/Damoscky/Cron_Job.git
```

- Install dependencies
```
cd name && composer install
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
- Next, create a new database and reference its name and username/password in the projects .env file. Below the database name is "expanse"
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=cron_job
DB_USERNAME=root
DB_PASSWORD=
```

- Go to your gmail account and get your gmail domain and secret key. choose an email and senders name. If your gmail is not activated for third party use, kindly activate.
```
MAILGUN_DOMAIN=****
MAILGUN_SECRET=****
MAIL_FROM_ADDRESS=***@***.com
MAIL_FROM_NAME=*****
```

### Step 3
- To start the server, run the command below
```shell
$ php artisan serve
```





