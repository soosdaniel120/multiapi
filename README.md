# Multi API
## Requirements
### [PhantomJS](https://github.com/soosdaniel120/phantomcookies#phantomjs)
### [Phantom Cookies](https://github.com/soosdaniel120/phantomcookies#install)
## Install
```
wget -O /tmp/multiapi.tar.gz https://github.com/soosdaniel120/multiapi/archive/refs/tags/v0.2.tar.gz
tar -xf /tmp/multiapi.tar.gz -C /tmp
rm -rf /tmp/multiapi.tar.gz
mv /tmp/multiapi-0.2 /var/www/multiapi
```
## Usage
multiapi-config.php
```
<?php

	$pattern = '/(?<host>http(s|):\/\/?([^\/]+)?)/';
	$url = '{$host}/wp-json/wp/v2/posts';
	$phantomcookies = 'http://localhost/phantomcookies/';

?>
```
## Logo
[psyonyx](https://www.fiverr.com/psyonyx)
