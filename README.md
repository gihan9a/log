<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Yii Logging Library</h1>
    <br>
</p>

This library provides [PSR-3] compatible logging library.
It is used in [Yii Framework] but is supposed to be usable separately.

[PSR-3]: https://www.php-fig.org/psr/psr-3/
[Yii Framework]: http://www.yiiframework.com/

[![Latest Stable Version](https://poser.pugx.org/yiisoft/log/v/stable.png)](https://packagist.org/packages/yiisoft/log)
[![Total Downloads](https://poser.pugx.org/yiisoft/log/downloads.png)](https://github.com/yiisoft/log/actions?query=workflow%3Abuild)
[![Build status](https://github.com/yiisoft/log/workflows/build/badge.svg)](https://github.com/yiisoft/log/actions?query=workflow%3Abuild)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/yiisoft/log/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/log/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/yiisoft/log/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/log/?branch=master)
[![Mutation testing badge](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Fbadge-api.stryker-mutator.io%2Fgithub.com%2Fyiisoft%2Flog%2Fmaster)](https://dashboard.stryker-mutator.io/reports/github.com/yiisoft/log/master)
[![static analysis](https://github.com/yiisoft/log/workflows/static%20analysis/badge.svg)](https://github.com/yiisoft/log/actions?query=workflow%3A%22static+analysis%22)
[![type-coverage](https://shepherd.dev/github/yiisoft/log/coverage.svg)](https://shepherd.dev/github/yiisoft/log)

## Logging targets

Logging targets are implemented as separate packages:

- [Database](https://github.com/yiisoft/log-target-db)
- [Email](https://github.com/yiisoft/log-target-email)
- [File](https://github.com/yiisoft/log-target-file)
- [Syslog](https://github.com/yiisoft/log-target-syslog)

### Unit testing

The package is tested with [PHPUnit](https://phpunit.de/). To run tests:

```shell
./vendor/bin/phpunit
```

### Mutation testing

The package tests are checked with [Infection](https://infection.github.io/) mutation framework. To run it:

```shell
./vendor/bin/infection
```

### Static analysis

The code is statically analyzed with [Psalm](https://psalm.dev/). To run static analysis:

```shell
./vendor/bin/psalm
```

### Support the project

[![Open Collective](https://img.shields.io/badge/Open%20Collective-sponsor-7eadf1?logo=open%20collective&logoColor=7eadf1&labelColor=555555)](https://opencollective.com/yiisoft)

### Follow updates

[![Official website](https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat)](https://www.yiiframework.com/)
[![Twitter](https://img.shields.io/badge/twitter-follow-1DA1F2?logo=twitter&logoColor=1DA1F2&labelColor=555555?style=flat)](https://twitter.com/yiiframework)
[![Telegram](https://img.shields.io/badge/telegram-join-1DA1F2?style=flat&logo=telegram)](https://t.me/yii3en)
[![Facebook](https://img.shields.io/badge/facebook-join-1DA1F2?style=flat&logo=facebook&logoColor=ffffff)](https://www.facebook.com/groups/yiitalk)
[![Slack](https://img.shields.io/badge/slack-join-1DA1F2?style=flat&logo=slack)](https://yiiframework.com/go/slack)

## License

The Yii Logging Library is free software. It is released under the terms of the BSD License.
Please see [`LICENSE`](./LICENSE.md) for more information.

Maintained by [Yii Software](https://www.yiiframework.com/).
