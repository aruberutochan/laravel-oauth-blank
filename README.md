# Laravel OAuth Blanl

This is a starting install of Laravel, with OAuth enabled

## Getting Started

Clone the repository and enter in the created folder
```
git clone git@github.com:aruberutochan/laravel-oauth-blank.git
cd laravel-oauth-blank
```

### Prerequisites

You need to run this command to have a full installation

#### Configure Database
Make sure you have a .env file with the database confiuration set.
You can use a copy of the .env.example file

```
cp .env.example .env
```
Edit .env to setup database

```
(...)
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=YourDataBaseName
DB_USERNAME=YourUserName
DB_PASSWORD=secret
(...)

```
#### Artisan configuration commands 
