# Alpine + composer
 - PHP-Version: 7.0.6

# Including
 - PHP 7.*
 - phpunit (/usr/local/bin/composer)
 
# How to run?
docker run --rm -w=[your working directory] shito/alpine-composer:edge [composer command]

The default working directory is /usr/share/nginx/html if -w option is not set