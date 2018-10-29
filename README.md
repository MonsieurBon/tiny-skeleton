# Tiny PHP Framework Skeleton Application

This is a skeleton application to quickly start a new project with the Tiny PHP framework. Use composer to create a new
project.

## Create new Project

Run this command from the directory in which you want to create the project

```bash
php composer.phar create-project monsieurbon/tiny-skeleton [new-app-name]
```

Replace `[new-app-name]` with the directory name for your new application.

### Webserver
#### Built-in PHP webserver
To start using the skeleton application run

```bash
php -S 127.0.0.1:8080 -t web/ web/index.php
```

This will start the hello world application. Point your browser at `http://localhost:8080/hello/World`. 

#### Apache, Nginx, etc.
Make sure you configure your webroot to be `web/`.