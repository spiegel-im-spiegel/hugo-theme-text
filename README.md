# Simple Text (Hugo Theme)

[![GitHub license](https://img.shields.io/badge/license-CC0-blue.svg)](https://raw.githubusercontent.com/spiegel-im-spiegel/hugo-theme-text/master/LICENSE)

"Simple Text" is simple theme for Text Site.

![Simple Text](https://farm1.staticflickr.com/718/21069070064_9331d16711_o.png)

## Installation & Usage

Clone this repository to your hugo theme directory.

	$ git clone https://github.com/spiegel-im-spiegel/hugo-theme-text.git themes/hugo-theme-text
	$ hugo server --theme=hugo-theme-text --buildDrafts --watch

## Configuration

In this theme you can add variables to your site config file. The following is the example config:

```toml:config.toml
theme           = "hugo-theme-text"
baseurl         = "http://example.com"
title           = "Yuor Site Name"
languageCode    = "ja" #ISO639/RFC4646 #optional
disqusShortname = "Disqus Short Name" #optional

[author]
name      = "Your Name"
url       = "URL for Your Profile" #optional
avatar    = "URL for Your icon (50×50)" #optional
license   = "CC-License: [by|by-sa|by-nc|by-nc-sa|by-nd|by-nc-nd|cc0]" #optional
github    = "Your GitHub ID" #optional
twitter   = "Your Twitter ID" #optional
medium    = "'@' + Your Medium ID" #optional
tumblr    = "Your Tumblr ID" #optional
instagram = "Your Instagram ID" #optional
flickr    = "Your Flickr ID" #optional
facebook  = "Your Facebook ID" #optional
linkedin  = "Your LinkedIn ID" #optional
flattr    = "Your Flattr ID" #optional

[params]
since       = "2015-01-01" #datetime format #optional
description = "Site Description" #optional
favicon     = "/favicon.ico" #optional
```

## License

These codes are licensed under CC0.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/)
