# This is php devlop template project

## Getting Started

+ init commond

```sh
$ docker-compose up -d --build
```

+ public dir is src/public
  + create index.php

```php
<?php 

phpinfo();
```

+ url:`http://localhost:8888/index.php`


## Docker images

+ php:8.2-fpm
+ nginx:1.20-alpine
+ mysql:5.7
