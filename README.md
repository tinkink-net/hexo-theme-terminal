# hexo-theme-terminal

Terminal theme for Hexo.

## Install & Usage 安装使用

```sh
npm install hexo-theme-terminal
```

Then, change your theme to `terminal`:

然后修改配置文件，将主题改为`terminal`即可：

```yaml
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: terminal
```

Theme has two languages: `en-us` and `zh-cn`, you can change the language by setting `language` in `_config.yml`:

主题内置了`en-us`和`zh-cn`两种语言，可通过`language`配置来指定：

```yaml
language: zh-cn
```

## Configuration 配置

You can set the following configuration in `theme_config`:

在`theme_config`配置中，可以使用以下配置项：

- `menus` An object, to config top navbar 一个对象，用于配置博客的顶部导航栏
- `favicon` A string, specify favicon file 一个字符串，用于配置博客的favicon
- `footers` An object, contains links in footer (e.g. copyright links) 一个对象，用于配置博客底部的链接信息（如版权链接、备案链接等）
- `google_analytics` An object to config google analytics, put the id in `tracking_id` property 一个对象，用于配置博客的Google Analytics，将ID写在`tracking_id`属性中

example 示例：

```yaml
theme_config:
  menus:
    首页: /
    月度报告: /categories/月度报告
    关于: /about/
  favicon: '/favicon.png'
  footers:
    '&copy; 麦芽糖': 'https://maiyatang.co'
  google_analytics:
    tracking_id: G-XXXXXXXXX
```

Demo: <https://blog.maiyatang.co>

## History 历史记录

### 1.0.0（2021-12-15）

- initial release 首次发布
