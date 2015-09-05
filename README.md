# Simple Text (Hugo Theme)

"Simple Text" is simple theme for Text Site.

## Installation & Usage

Clone this repository to your hugo theme directory.

	$ git clone https://github.com/spiegel-im-spiegel/hugo-theme-text.git themes/hugo-theme-text
	$ hugo server --theme=hugo-theme-text --buildDrafts --watch

## Configuration

In this theme you can add variables to your site config file. The following is the example config:

```toml:config.toml
baseurl      = "http://text.baldanders.info/"
title        = "text.Baldanders.info"
languageCode = "ja"

[params]
description = "帰ってきた「しっぽのさきっちょ」"
favicon     = "/favicon.ico"

[params.author]
name        = "Spiegel"
profileurl  = "http://www.baldanders.info/spiegel/profile/"
avatar      = "/images/avatar.jpg"
license     = "by-sa"
github      = "spiegel-im-spiegel"
twitter     = "spiegel_2007"
medium      = "@spiegel"
instagram   = "spiegel_2007"
facebook    = "spiegel.im.spiegel"
linkedin    = "spiegelimspiegel"
flattr      = "spiegel"
```

## License

These codes are licensed under CC0.

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/)
