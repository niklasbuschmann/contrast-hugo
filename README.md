Adaption of the of [contrast](https://github.com/niklasbuschmann/contrast) Jekyll theme.

## Installation

To install Contrast as your default theme, first install this repository in the `themes/` directory:

    $ cd themes/
    $ git clone https://github.com/niklasbuschmann/contrast-hugo.git

Second, specify `contrast-hugo` as your default theme in the `config.toml` file. Just add the line

    theme = "contrast-hugo"

at the top of the file.

### Example config

```
title = "Davids Blog"
author = "David Wallace"
theme = "contrast-hugo"

[params]
  minimal = false
  excerpts = false
  description = "my blog"

[menu]
  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 10
```

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [KaTeX](https://katex.org/)

## License

[public domain](http://unlicense.org/)
