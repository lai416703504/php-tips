# 多版本php使用composer
```shell
# 7.2版本composer 使用composer72命令
vi /usr/local/bin/composer72
```

```shell
#!/bin/bash
# 就是 php对应版本路径 + composer.phar路径 + $*
/www/server/php/72/bin/php /usr/bin/composer $*
```
