This is a port of the [Arabica theme for Ghost](https://github.com/slunsford/arabica) to Hugo. You can find a live demo [here](https://arabica.netlify.com).

![Preview](/images/screenshot.png)

## Quickstart

### Install

Inside the folder of your Hugo site run:

```
$ cd themes
$ git clone https://github.com/nirocfz/arabica
```

### Preview exampleSite

```
$ cd arabica/exampleSite
$ hugo server --themesDir ../..
```

### Configure Hugo

Add the folling line to `config.toml` to use the theme

```
theme = "arabica"
```

This is the `config.toml` of [exampleSite](/exampleSite)

```
baseurl = "https://example.org/"
title = "Arabica"
author = "John Doe"
canonifyurls = true
paginate = 3
theme = "arabica"

[params]
    description = "A minimal Hugo theme"
    replaceGoogleFonts = "fonts.loli.net"
    twitter = "example"
    facebook = "example"
```

Thanks

* [Hugo](https://gohugo.io/)
* [slunsford/arabica](https://github.com/slunsford/arabica)
* [xianmin/hugo-theme-jane](https://github.com/xianmin/hugo-theme-jane)

## License

See [LICENSE](/LICENSE.md)
