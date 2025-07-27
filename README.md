Adaption of the of [contrast](https://github.com/niklasbuschmann/contrast) Jekyll theme.

## Installation

To install Contrast as your default theme, first install this repository in the `themes/` directory:

    $ cd themes/
    $ git clone https://github.com/niklasbuschmann/contrast-hugo.git

Second, specify `contrast-hugo` as your default theme in the `config.toml` file. Just add the line

    theme = "contrast-hugo"

at the top of the file.

An example `hugo.yaml` could look like this:

```yaml
params:
  excerpts: true

menu:
  main:
  - {name: "Home", url: "/", identifier: "home", weight: 1}
  - {name: "About", url: "/about/", identifier: "address-card", weight: 2}
  social:
  - {name: "Mail", url: "mailto:", identifier: "envelope", weight: 3}
  - {name: "Github", url: "https://github.com/", identifier: "github", weight: 4}
  - {name: "Subscribe", url: "/index.xml", identifier: "rss", weight: 5}

```
