# Lux

A minimalism theme for [Hexo] forked from [Light](https://github.com/hexojs/hexo-theme-light)

[Demo](http://sololand.moe)

## Install

Execute the following command and modify `theme` in `_config.yml` to `lux`.

```
git clone https://github.com/brglng/hexo-theme-lux.git themes/lux
```

## Update

Execute the following command to update Lux.

```
cd themes/lux
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

baidu_share:
  enable: true

gitalk:
  enable: true

fancybox: true

rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **baidu_share** - Share buttons at the bottom of articles
  (Powered by Baidu Share)
  - **enable** - Enable share buttons
- **gitalk** - Comment system powered by Gitalk
  - **enable** - Enable Gitalk comments
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **baidu_analytics** - Baidu Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

## Features

### Baidu Share Support
In *theme's* `_config.yml`:
```yaml
baidu_share:
  enable: true
```

### Gitalk Support
In *themes's* `_config.yml`:
```yaml
gitalk:
  enable: true
```

In *site's* `_config.yml`:
```yaml
gitalk:
  client_id: <client ID>
  client_secret: <client secret>
  repo: <repo>
  owner: <owner>
  admin: <admin>
  distraction_free_mode: false
```

### Googla Analytics and Baidu Statistics Support
In *site's* `_config.yml`:
```yaml
google_analytics: <Google Analytics ID>
baidu_statistics: <Baidu Statistics ID>
```

### _Links_ Widget
In *site's* `_config.yml`:
```yaml
links:
  Hexo: https://hexo.io
  Lux: https://github.com/brglng/hexo-theme-lux/
```

### Google/Baidu Search Switcher
In the search widget, Google/Baidu can be selected

### "Powered By" Information in Footer
In *site's* `_config.yml`:
```yaml
powered_by:
  Hexo: https://hexo.io/
  Lux: https://github.com/brglng/hexo-theme-lux
```

### Gallery Post

![](http://i.minus.com/ibp6Hbytwgof9y.jpg)

```
---
layout: photo
title: Gallery Post
photos:
- http://i.minus.com/ibobbTlfxZgITW.jpg
- http://i.minus.com/iedpg90Y0exFS.jpg
---
```

### Link Post

![](http://i.minus.com/i7hBbGqh14EWo.png)

```
---
layout: link
title: Link Post
link: http://www.google.com/
---
```

### Fancybox

![](http://i.minus.com/iHv7h7rZNqHvo.PNG)

[Hexo]: http://zespia.tw/hexo/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/
