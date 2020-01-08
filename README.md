# Wordpress as Submodule

Example of a project using Wordpress Core, as well as plugins and themes, as submodules.

## Prerequisites

* PHP7.*

## Installing

1. Clone the project recursively
  ```
  git clone --recursive https://github.com/DenisUyeda/wordpress_as_submodule.git
  ```
  or
  ```
  git clone --recursive git@github.com:DenisUyeda/wordpress_as_submodule.git
  ```
2. Enter the directory and run setup.sh
  ```
  cd wordpress_as_submodule
  bash setup.sh
  ```
3. Update your database data on wp-config.php;
4. Start a server and test it;
  Example
  ```
  php -S localhost:3000 -t .
  ```
5. Access the server. This should work like a normal Wordpress installation.

## Todo

* Make wp-admin accessible by [domain]/wp-admin. Right now, it only works as [domain]/wordpress/wp-admin
