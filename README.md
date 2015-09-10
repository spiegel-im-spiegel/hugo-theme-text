# Simple Text (Hugo Theme)

"Simple Text" is simple theme for Text Site.

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
languageCode    = "ja"
disqusShortname = "Disqus Short Name" #optional

[params]
description = "Site Description" #optional
favicon     = "/favicon.ico" #optional

[params.author]
name      = "Your Name"
url       = "URL for Your Profile" #optional
avatar    = "URL for Your icon (50×50)" #optional
license   = "CC-License: [by|by-sa|by-nc|by-nc-sa|by-nd|by-nc-nd|cc0]" #optional
github    = "Your GitHub ID" #optional
twitter   = "Your Twitter ID" #optional
medium    = "'@' + Your Medium ID" #optional
instagram = "Your Instagram ID" #optional
facebook  = "Your Facebook ID" #optional
linkedin  = "Your LinkedIn ID" #optional
flattr    = "Your Flattr ID" #optional
```

## License

These codes are licensed under CC0.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/)
