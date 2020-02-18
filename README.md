Adaption of the of [contrast](https://github.com/niklasbuschmann/contrast) Jekyll theme.

## Installation

To install Contrast as your default theme, first install this repository in the `themes/` directory:

    $ cd themes/
    $ git clone https://github.com/niklasbuschmann/contrast-hugo.git

Second, specify `contrast-hugo` as your default theme in the `config.yaml` file. Just add the line

    theme: "contrast-hugo"

at the top of the file.

## Sidebar

Instead of the horizontal menu, a sidebar can be enabled with `sidebar: true`. See [here](https://niklasbuschmann.github.io/contrast/) for an example of the sidebar in action.

An example `config.yaml` section could look like this:

```yaml
params:
  sidebar: true
  show_excerpts: true
  description: 'Made by <a href="">Blog Author</a>'

menu:
  main:
  - {name: "Home", url: "/", identifier: "home", weight: 1}
  - {name: "About", url: "/about/", identifier: "address-card", weight: 2}
  remote:
  - {name: "Mail", url: "mailto:", identifier: "envelope", weight: 3}
  - {name: "Github", url: "https://github.com/", identifier: "github", weight: 4}
  - {name: "Subscribe", url: "/index.xml", identifier: "rss", weight: 5}

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
