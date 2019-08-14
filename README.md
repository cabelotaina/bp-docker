# Docker BP

This is a docker for [bota pressão](https://github.com/redelivre/botapressao) plugin development.

## Setting

Install docker on your Operational System and run on console `docker-compose up`

If you want develop a new theme add a new line for your theme on `docker-compose.yml` file:

```
    volumes:
      - ./BotaPressao:/var/www/html/wp-content/plugins/BotaPressao
      - ./theme-name:/var/www/html/wp-content/themes/theme-name
```

## Get more informations on ...

[wp-docker tutorial](https://russt.me/2017/04/using-docker-for-wordpress-theme-plugin-development)
[docker oficial page](https://www.docker.com/products/container-runtime)