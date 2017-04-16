# Docker: Gitlab PHP 7 CI

Used this docker image with Gitlab CI for Docker executor. This image is based on my image [voduytuan/docker-nginx-php7](https://github.com/voduytuan/docker-nginx-php7) with pre-installed PHP 7, Nginx.


## Contents
 * PHP 7.0
 * [Composer](https://getcomposer.org/)
 * [PHPUnit](http://phpunit.de/)
 * [PHP Copy/Paste Detector - phpcpd](https://github.com/sebastianbergmann/phpcpd)
 * [PHP Dead Code Detector - phpdcd](https://github.com/sebastianbergmann/phpdcd)
 * [Measuring the size and analyzing the structure of a PHP project - phploc](https://github.com/sebastianbergmann/phploc)
 * [PHP software metrics - pdepend](http://pdepend.org/)
 * [PHP Code sniffer- phpcs](http://pear.php.net/package/PHP_CodeSniffer)
 * [PHP Mess Detector - phpmd](http://phpmd.org/)
 * [Full-stack testing PHP framework - Codeception](http://codeception.com)
 * [PHP Static Analysis Tool  - phpstan](https://github.com/phpstan/phpstan)


## Get it
```sh
docker pull voduytuan/gitlab-php7-ci
```

## Run it
```sh
docker run --rm -i -t voduytuan/gitlab-php7-ci
```
Docker's [run command reference manual](http://docs.docker.io/en/latest/reference/run/)