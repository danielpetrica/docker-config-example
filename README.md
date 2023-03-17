# docker-config-example


## Initial creation of a laravel project
You can spin the bootstrap of a laravel project with this command

```
 docker run  \
    -v ${PWD}/:/var/www/html <php image name> \
    /usr/bin/composer  create-project --prefer-dist laravel/laravel <directory name> '<laravel version>'
```
After that your laravel project will be available in the `<directory name>` folder



