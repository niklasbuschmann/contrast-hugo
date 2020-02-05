Adaption of the of [contrast](https://github.com/niklasbuschmann/contrast) Jekyll theme.

## Installation

To install Contrast as your default theme, first install this repository in the `themes/` directory:

    $ cd themes/
    $ git clone https://github.com/niklasbuschmann/contrast-hugo.git

Second, specify `contrast-hugo` as your default theme in the `config.yaml` file. Just add the line

    theme: "contrast-hugo"

at the top of the file.

## Sidebar

Instead of the horizontal menu, a sidebar can be enabled with `sidebar: true`. See [here](https://niklasbuschmann.github.io/contrast/) for an example of the sidebar in action. Adding a `hidden` class to the icon tag will hide the icon on mobile devices.

An example `config.yaml` section could look like this:

```yaml
params:
  sidebar: true
  fontawesome: true
  description: 'Made by <a href="">Blog Author</a>'

menu:
  main:
  - identifier: "home"
    name: "Home"
    url: "/"
    weight: 1
    pre: "<span class='fas fa-home hidden'></span>"
  - identifier: "about"
    name: "About"
    url: "/about/"
    weight: 2
    pre: "<span class='fas fa-address-card hidden'></span>"
  - identifier: "github"
    name: "Github"
    url: "https://github.com/"
    weight: 3
    pre: "<span class='fab fa-github hidden'></span>"
  - identifier: "feed"
    name: "Subscribe"
    url: "/index.xml"
    weight: 4
    pre: "<span class='fas fa-rss hidden'></span>"
```

## Features

 - supports dark mode on macOS Mojave
 - optional sidebar
 - MathJax support
 - no external resources
 - responsive

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [KaTeX](https://katex.org/)
- [Font-Awesome](https://fontawesome.com/)

## License

[public domain](http://unlicense.org/)
