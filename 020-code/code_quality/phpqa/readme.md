# phpqa {#phpqa}

> [https://github.com/jakzal/phpqa](https://github.com/jakzal/phpqa)

Docker image that provides static analysis tools for PHP.

Using the single PHPQA image, you'll be able to run a lot of tools like `phan`, `php_codesniffer`, `php-cs-fixer`, `phpcpd`, `phpmd`, `phpmnd`, `phpstan` and much more.

Just install PHPQA and specify the tool you want to run on the command line like f.i. `docker run -it --rm -v "$(pwd):/project" -v "$(pwd)/tmp-phpqa:/tmp" -w /project jakzal/phpqa phpcs` and followed by the correct arguments.

