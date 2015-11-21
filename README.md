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

widgets:
- search
- tagcloud
- links

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: false
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

baidu_share:
  enable: true

fancybox: true

rss:
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the bottom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **baidu_share** - Share buttons at the bottom of articles
  (Powered by Baidu Share)
  - **enable** - Enable share buttons
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **baidu_analytics** - Baidu Analytics ID
- **bing_webmaster_tools** - Bing Webmaster Tools ID
- **rss** - RSS subscription link (change if using Feedburner)

## Features

### Disqus and Duoshuo Comments Simultaneously
If `disqus_shortname` and `duoshuo_shortname` are both set in your *site's*
`_config.yml`, both comment provider will be used, and there will be a
switcher above them. If only one of them is set, it will be used and there
will be no switcher.
```yaml
disqus_shortname: <disqus shortname>
duoshuo_shortname: <duoshuo shortname>
```

### Baidu Share Support
In *theme's* `_config.yml`:
```yaml
baidu_share:
  enable: true
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

### Tweet Widget

![](http://i.minus.com/iMC8EyF9y0Y3y.PNG)

### Fancybox

![](http://i.minus.com/iHv7h7rZNqHvo.PNG)

[Hexo]: http://zespia.tw/hexo/
[AddThis]: https://www.addthis.com
[Fancybox]: http://fancyapps.com/fancybox/
