<p align="center"><img src="./docs/logo.png" height="150" alt="logo"/></>
<h1 align="center">PHP Coverage and Documentation 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/alphaolomi/php-cover#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>

<a href="https://travis-ci.org/alphaolomi/php-cover">
<img alt ="ico-travis" src="https://img.shields.io/travis/com/alphaolomi/php-cover?logo=travis&style=flat-square" >
</a>
<a href="https://scrutinizer-ci.com/g/alphaolomi/php-cover/code-structure">
<img alt ="ico-codecov" src="https://img.shields.io/codecov/c/github/alphaolomi/php-cover?logo=codecov&style=flat-square" >
</a>

  <a href="https://github.com/alphaolomi/php-cover/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://github.com/alphaolomi/php-cover/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/github/license/alphaolomi/php-cover" />
  </a>
  <a href="https://twitter.com/alphaolomi" target="_blank">
    <img alt="Twitter: alphaolomi" src="https://img.shields.io/twitter/follow/alphaolomi.svg?style=social" />
  </a>
</p>

## TOC

Typed Properties
Arrow Functions
Limited Return Type Covariance and Argument Type Contravariance
Unpacking Inside Arrays
Numeric Literal Separator
Weak References
Allow Exceptions from `__toString()`
Opcache Preloading
Several Deprecations
Extensions Removed from the Core

## Why use Docker?
I won't go into too much detail what Docker is and why you should use it, because others have already talked about this extensively.

As for me, my main reasons were

- Setup in the team involved a lot of work
- I wanted to learn Docker for quite some time because you hear a lot about it

## Links

### General
- https://www.php.net/releases/7_4_0.php
- https://stitcher.io/blog/new-in-php-74

### Docker
- https://blog.jetbrains.com/phpstorm/2018/08/quickstart-with-docker-in-phpstorm/
- https://www.pascallandau.com/blog/php-php-fpm-and-nginx-on-docker-in-windows-10/

### 🏠 [Homepage](https://github.com/alphaolomi/php-cover#readme)

### ✨ [Demo](https://github.com/alphaolomi/php-cover)

## Getting started

### Install

```sh
composer require alphao/php-cover
```

### Usage

```php
$example = new App\Cover\Example();
echo $example->echoPhrase('Hello, League!');
```

### Run tests

```sh
composer test
```

## Generate docs
```
./vendor/bin/phpdoc ./src -t ./docs
```

## ⏩ Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently

## Author

👤 **Alpha Olomi**

-   Website: https://alphaolomi.me
-   Twitter: [@alphaolomi](https://twitter.com/alphaolomi)
-   Github: [@alphaolomi](https://github.com/alphaolomi)
-   LinkedIn: [@alphaolomi](https://linkedin.com/in/alphaolomi)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/alphaolomi/php-cover/issues). You can also take a look at the [contributing guide](https://github.com/alphaolomi/php-cover/blob/master/CONTRIBUTING.md).

## 🔒 Security

If you discover any security related issues, please email hello@alphaolomi.com instead of using the issue tracker.

## Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.patreon.com/alphaolomi">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## 📝 License

Copyright &copy; 2020 [Alpha Olomi](https://github.com/alphaolomi).<br />
This project is [MIT](https://github.com/alphaolomi/php-cover/blob/master/LICENSE) licensed.

---

_This README was generated partly with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
