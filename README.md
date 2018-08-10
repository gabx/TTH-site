# Material-Design-TTH

Material-Design-TTH is a simple responsive [material design](https://material.io/design/) theme for [Hugo](http://gohugo.io/).


demo : [http://www.thetradinghall.com/](http://www.thetradinghall.com/)

## Features


## Installation

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/gabx/material-design-tth
```

## Usage

```shell
$ hugo server -t material-design-tth -w -D
```

## Configuration

config.toml

```toml
theme="material-design-tth"
baseurl = "Your Site URL"
languageCode = "en-us"
title = "Your Site Title"
MetaDataFormat = "toml"
copyright = "MIT"

[params]
  description = "Your Site Description" # optional
  twitter = "Your Twitter Name" # optional
  github = "Your Github Name" # optional
  facebook = "Your facebook Name" # optional
  gplus = "Your Google+ profile name" # optional
  linkedin = "Your LinkedIn Name" # optional
  headerCover = "images/headerCover.png" # optional
  footerCover = "images/footerCover.png" # optional
  googleAnalyticsUserID = "Your Analytics User Id" # optional

[permalinks]
  post = "/:year/:month/:day/:title/" # optional
```

