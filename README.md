Tachyons
==========

Tachyons is a responsive & fast [Hugo](http://gohugo.io) theme made using the amazing [TACHYONS](http://www.tachyons.io) CSS framework & [GEOMICONS](http://geomicons.com).

![Tachyons screenshot](https://github.com/marloncabrera/tachyons/blob/master/images/tn.png)

## Contents

- [Options](#options)
  - [Header](#header)
  - [Footer](#footer)
- [Author](#author)
- [License](#license)

## Options

Customize your blog editing the header & footer under themes/tachyons/layouts/partials/ directory.


### Header

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=Edge">
    <meta name="author" content="Marlon Cabrera Oliveira">
    <meta name="description" content="Hugo theme using tachyons.io & geomicons.com">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="http://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700" rel="stylesheet">
    <link rel="stylesheet" href="http://fonts.googleapis.com/css?family=PT+Sans:400,700,400italic,700italic|PT+Mono&amp;subset=latin,cyrillic">
    <link rel="stylesheet" href="/css/tachyons.css">
    <style>
        .geomicon { width: 1.5em; height: 1.5em; color: #405660; }
        body{ font-family:'PT Sans', sans-serif; }
    </style>
  </head>
  <body>
      <header class="tc pal bb b-near-white">
    <h1 class="f6 thin i link-child"><a href="/">Your_blog_name_here</a></h1>
        <nav>
          <ul class="list pln">
            <li class="dib prm"><a href="/"><span class="js-geomicon geomicon" data-icon="home"></span>Home</a></li>
            <li class="dib prm"><a href="/post"><span class="js-geomicon geomicon" data-icon="compose"></span>Blog</a></li>
            <li class="dib prm"><a href="/about"><span class="js-geomicon geomicon" data-icon="user"></span>About</a></li>
          </ul>
        </nav>
        </header>
```



