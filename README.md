# Solar Theme for Hugo

A minimalistic theme for [Hugo](https://gohugo.io/) blogs, fork of
[Solar Theme for Hugo](https://github.com/bake/solar-theme-hugo).

## Color schemes

Solar offers three color schemes: 
* (Solarized) `light`
* (Solarized) `dark`
* (Solarized) `gray`

Additionally there is a `preference` setting which
switches between `light` and `dark` according to the users preference.
[example config.toml](exampleSite/config.toml) for a starting point.

## Code Highlight
on the base. add code highlight with highlight.js and choose a style which most cool here.

## Show post's Tags, Categories, Reading time
Show Reading time when more than 1 minutes (Auto compute from content length, 220 words/mins).

Show Tags, Categories when you add those info on post header
```
---
title: "Demo"
date: 2021-08-31T06:00:00+08:00
categories: ["Themes"]
tags: [":)"]
---
```

## Installation
Same as with any other theme:

```bash
$ git clone https://github.com/LunziQwQ/solar-theme-hugo themes/solar-theme-hugo
$ hugo server --theme solar-theme-hugo
```

## License

GPLv2 or higher
