# symblog tutorial - Creating a blog in Symfony2

## Introduction

This project is the documentation source for the symblog tutorial located at
http://tutorial.symblog.co.uk

Full details of this project can be found at the
[symblog tutorial](http://tutorial.symblog.co.uk) site.

The demo site for this project can be found at http://symblog.co.uk

## Installing

 1. Clone the repository
 2. Rename 'app/config/parameters.ini.dist' to 'app/config/parameters.ini'
 3. Run 'php bin/vendors install' to install all the required vendors
 4. Install the assets with 'php app/console assets:install web'
 5. Create the database with 'php app/console doctrine:database:create'
 6. Update schema with 'php app/console doctrine:schema:create'
 7. Load fixtures with 'php app/console doctrine:fixtures:load'

## Updating to Symfony 2.0.4

If you already have a clone of the repo you will need to update your vendors by running

```
$ php bin/vendors install
$ php app/console cache:clear
```

More information can be found on the [Symfony 2 blog](http://symfony.com/blog)

