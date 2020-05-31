# Introduction

fork from https://github.com/micooz/docker-lnmp

# Update
  disabled https port, prefer to use another nginx server as reverse proxy transfer requests to this one

  need to install php pdo

  ```
  docker exec -it docker-lnmp_fpm_ /bin/bash
  ```

  then

  ```
  docker-php-ext-install pdo pdo_mysql
  ```

  set mysql default password