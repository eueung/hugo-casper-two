# Casper Two

[Casper Two](https://github.com/eueung/hugo-casper-two) is a port of the [Casper](https://github.com/TryGhost/Casper), the default personal blogging theme for Ghost. While a legacy version (v1.x) has [already been ported](https://github.com/vjeantet/hugo-theme-casper) to Hugo years ago, it is incompatible with the recent 2.x version. So I ended up porting this new Casper version. 

![Screenshot](https://raw.githubusercontent.com/eueung/hugo-casper-two/master/images/screenshot.png)

## Theme Demo

- [telematika.org](https://telematika.org/)
- sample site - [github pages](https://eueung.github.io/hugo-casper-two/)

## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/eueung/hugo-casper-two.git casper-two

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

## Sample Configuration

The following `config.toml` is used for the demo site. 

```toml
baseurl         = "/"
theme           = "casper-two"
languageCode    = "en-US"
disqusShortname = ""
paginate        = 6
#SectionPagesMenu = "main"

[params]
  title       = "Hugo Casper Two"
  subtitle    = "Port of Casper 2.x for Hugo"

  cover       = "img/blog-cover.jpg"
  description = "Here is a description of your site."
  metaDescription = ""
  googleAnalytics = ""
  customCSS = []
  RSSLink = ""

  twitterName = "faketryghost"
  fbName = "fakeghost"
  githubName = "eueung"

  logo = "hugo-logo.png"
  orgName = "EM"
  orgWebsite = "https://www.telematika.org"
  orgDescription = "Here is a description placeholder for your org"

  author = "EM"
  authorAvatar = "img/ghost-icon.png"
  authorLocation = "Bandung, ID"
  authorWebsite = "https://eueung.github.io"
  authorDescription = "Describe yourself.."

  pageNotFoundTitle = "404 - Page not found"

  #casper or caspertwo
  singleViewStyle = "casper"

[permalinks]
  post = "/:slug/"

[[menu.main]]
  name = "Home"
  url = "/"
  weight = 200

[[menu.main]]
  name = "Go"
  url = "/tags/golang/"
  weight = 100

[[menu.main]]
  name = "Food"
  url = "/categories/food/"
  weight = 99

[[menu.main]]
  name = "External"
  url = "https://google.com/"
  weight = 95
```

Sample content structure is given in the `exampleSite` folder. Have fun!

![Screenshot](https://raw.githubusercontent.com/eueung/hugo-casper-two/master/images/telematika1.jpg)
![Screenshot](https://raw.githubusercontent.com/eueung/hugo-casper-two/master/images/telematika2.jpg)

## License

This theme is released under the MIT license. For more information read the [License](//github.com/eueung/hugo-casper-two/blob/master/LICENSE.md).


