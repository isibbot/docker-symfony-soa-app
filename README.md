# docker-smyfony-soa

### Intent

This project is an learning and example into using..

* Docker (Via Dockerfile and docker-compose)
* Composer
* Symfony
  * Doctrine
* Mysql

With a final aim to produce a simple REST api with symfony which will be consumed by one of the plethora of modern Javascript frameworks.

### Usage

Bring everything up, db, backend, front-end.

`/infrastructure docker-compose up`

http://localhost:8082 Front-end angular app


### Prerequisites

This isnt needed as such, just a reminder to myself how I originally set the project up. Gotchas, pitfalls etc.

##### PHP and some of its pals.

```
sudo apt-get install php-Mysql
sudo apt install php-xml
```

Pre-empt symfony from complaining and set php.ini `date.timezone = Europe/London`

`sudo vi /etc/php/7.0/cli/php.ini`

##### Composer
`sudo apt install composer`

##### Symfony

Locally install symfont to create your app.
```
sudo mkdir -p /usr/local/bin
sudo curl -LsS https://symfony.com/installer -o /usr/local/bin/symfony
sudo chmod a+x /usr/local/bin/symfony
```


