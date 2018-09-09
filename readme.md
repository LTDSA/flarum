![Flarum](https://flarum.org/img/logo.png)

**[Flarum](https://flarum.org/) 是一款免费、开源的社区软件。**它通过PHP和[Mithril.js](https://mithril.js.org/)建立。It is:

* **简单**, with a responsive UI that is optimized for touch devices
* **快速**, with a total JS payload size of ~130 KB gzipped
* **扩展**, so you can tailor it to your use-case

![screenshot](https://flarum.org/img/screenshot.png)

## 安装

> **Flarum is currently in beta and should not be used in production.** It is being developed openly on GitHub. Check out the [Roadmap](https://flarum.org/roadmap/) to follow along with our progress.

You must have SSH access to a server with **PHP 5.5+** and **MySQL 5.5+**, and install [Composer](https://getcomposer.org/).

```
composer create-project flarum/flarum . --stability=beta
```

阅读[Installation Guide](https://flarum.org/docs/installation/)来获取更多信息。

## 开发

This repository holds the Flarum skeleton application.
Its dependencies, such as [flarum/core](https://github.com/flarum/core) (where most development happens), have to be installed using [Composer](https://getcomposer.org/).

## 支持

Refer to the [FAQ](https://flarum.org/docs/faq/), [Documentation](https://flarum.org/docs/), and ask questions on the [社区论坛](https://discuss.flarum.org/) or [Discord Chat](https://flarum.org/discord/).

## Contributing

Flarum is open-source and we would love your help building it!请阅读[Contributing Guide](https://github.com/flarum/flarum/blob/master/CONTRIBUTING.md)来了解您可以帮助些什么。
## 协议

版权 (c) 2015 Toby Zerner。代码的发布遵循[MIT协议](https://github.com/flarum/flarum/blob/master/LICENSE)。
