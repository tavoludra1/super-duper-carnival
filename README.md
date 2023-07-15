# super-duper-carnival
Proyecto laravel

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>

This definition creates two containers, one for PHP and one for MariaDB. Code will attach to the PHP container, and from within that container the MariaDB container will be available on localhost port 3306. The MariaDB instance can be managed from the container's command line with:
```
mariadb -h localhost -P 3306  --protocol=tcp -u root --password=mariadb -D mariadb
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
