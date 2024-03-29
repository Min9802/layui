<p align="center">
  <a href="https://layui.dev">
    <img src="https://unpkg.com/outeres@0.1.0/img/layui/logo-icon.png" width="81" alt="Layui">
  </a>
</p>
<h1 align="center">Layui</h1>
<p align="center">
  Classic modular front-end UI library
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/layui">
    <img src="https://img.shields.io/npm/v/layui" alt="Version">
  </a>
  <a href="https://www.npmjs.com/package/layui">
    <img src="https://img.shields.io/github/license/layui/layui" alt="License">
  </a>
  <a href="https://github.com/layui/layui/blob/2.x/dist/css/layui.css">
    <img src="https://img.badgesize.io/layui/layui/2.x/dist/css/layui.css?compression=brotli&label=CSS%20Brotli%20size" alt="CSS Brotli size">
  </a>
  <a href="https://github.com/layui/layui/blob/2.x/dist/layui.js">
    <img src="https://img.badgesize.io/layui/layui/2.x/dist/layui.js?compression=brotli&label=JS%20Brotli%20size" alt="JS Brotli size">
  </a>
</p>

---

Layui is a collection of free and open source Web user interface component libraries. It uses its own lightweight module specifications and follows the original `HTML/CSS/JavaScript` development model. It is easy to get started and can be used immediately. Its style is simple and understated but the interior elegance is rich, every detail, including the documentation, is carefully crafted, making it perfect for quickly building web interfaces. Layui is different from popular front-end frameworks, but it does not go against the trend and believes in going back to nature. To be more precise, it is aimed at pragmatic people who pursue simplicity, that is, there is no need to use many different construction tools, just face the browser itself and you can get the elements. elements and interactions that the page needs to present

## Get started quickly

To use Layui, just add files to the page:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Quick Start - Layui</title>
    <link href="./layui/css/layui.css" rel="stylesheet" />
  </head>
  <body>
    <!-- HTML Content -->
    <script src="./layui/layui.js"></script>
    <script>
      // Usage
      layui.use(function () {
        var layer = layui.layer;
        // Welcome
        layer.msg("Hello World", { icon: 6 });
      });
    </script>
  </body>
</html>
```

## Documents

[**Documents current version**](https://layui.dev/docs/2/)

## Join the project

[project participants](https://github.com/layui/layui/graphs/contributors)

## Open source license

Layui use [MIT](https://opensource.org/licenses/MIT) Published with permission. Other relevant agreements may also be consulted《[Disclaimer](https://gitee.com/layui/layui/blob/main/DISCLAIMER.md)》。
