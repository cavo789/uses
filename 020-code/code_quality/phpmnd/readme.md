# PHP Magic Number Detector

> [https://github.com/povils/phpmnd](https://github.com/povils/phpmnd)

PHPMND will scan your code and search for number. For instance:

```php
if (mb_strlen($password) > 7) {
    throw new InvalidArgumentException("password");
}
```

and suggest to define a constant instead of hard-coding the number. With a constant, the code will immediately be more readable.

**The easiest way to use it is using [https://github.com/jakzal/phpqa](https://github.com/jakzal/phpqa).**
