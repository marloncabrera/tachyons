Tachyons
==========

Tachyons is a responsive & fast [Hugo](http://gohugo.io) theme made with the amazing [TACHYONS](http://www.tachyons.io) CSS framework & [GEOMICONS](http://geomicons.com).

Please see a demo site [here](http://marloncabrera.github.io/tachyons) and another example [here](http://nolram.com).

![Tachyons screenshot](https://github.com/marloncabrera/tachyons/blob/master/images/tn.png)

## Contents

- [Usage](#usage)
- [Options](#options)
  - [Header](#header)
  - [Footer](#footer)
  - [Icon Reference Table](#icon-reference-table)
- [Author](#author)
- [Credits](#credits)
- [License](#license)

## Usage

From [Hugo Quickstart](http://http://gohugo.io/overview/quickstart/):

* **Install Hugo**

Go to [Hugo Releases](https://github.com/spf13/hugo/releases) and download the appropriate version for your OS and architecture.
Save the main executable as *hugo* (or *hugo.exe* on Windows) somewhere in your PATH as we will be using it in the next step.
More complete instructions are available at [Installing Hugo](http://gohugo.io/overview/installing/).

* **Create a new site & install Tachyon Theme**

```
$ hugo new site /path/to/site
$ cd /path/to/site
$ mkdir themes
$ cd themes
$ git clone https://github.com/marloncabrera/tachyons.git
```

See [Options](#options) below to customize your blog.

* **Create Some Content**

```
$ hugo new post/first.md
```

* **Run Hugo and see the results**

```
$ hugo server --theme=tachyons --buildDrafts --watch
```

Open your browser at [http://localhost:1313](http://localhost:1313) to see the results.

## Options

Customize your blog editing the header & footer under themes/tachyons/layouts/partials/ directory.


### Header

Replace "Your_blog_name_here" to change your new Blog name.
If you need to create more sections, you have to add the section name to the nav menu like the example below, then pick up a specific icon from [Icon Reference Table](#icon-reference-table).


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    ...
    ...
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

### Footer

On footer.html you can customize or remove the links to Github or Twitter and include Google Analytics javascript code between the ```<script> ...</script>``` tags along with Geomicons portion.


```html
footer class="tc center bt b--near-white pvx phm pax-m phxl-l pvx-l">
<small class="f5 mw7 db center phm lh-copy">
<nav>
<ul class="list pln">
<li class="dib prm"><a href="https://www.github.com"><span class="js-geomicon geomicon blue" data-icon="github"></span></a></li>
<li class="dib prm"><a href="https://www.twitter.com"><span class="js-geomicon geomicon blue" data-icon="twitter"></span></a></li>
</ul>
</nav>
Copyright-  2015
</small>
</footer>
<script src="http://d2v52k3cl9vedd.cloudfront.net/geomicons/0.2.0/geomicons.min.js.gz"></script>
<script>
var icons = document.querySelectorAll('.geomicon');
Geomicons.inject(icons);
</script>
</body>
</html>
```


### Icon Reference Table

Icon    | ID
--------|--------
![bookmark](http://jxnblk.github.io/geomicons-open/icons/bookmark.svg) | bookmark
![calendar](http://jxnblk.github.io/geomicons-open/icons/calendar.svg) | calendar
![camera](http://jxnblk.github.io/geomicons-open/icons/camera.svg) | camera
![chat](http://jxnblk.github.io/geomicons-open/icons/chat.svg) | chat
![check](http://jxnblk.github.io/geomicons-open/icons/check.svg) | check
![chevron-down](http://jxnblk.github.io/geomicons-open/icons/chevron-down.svg) | chevron-down
![chevron-left](http://jxnblk.github.io/geomicons-open/icons/chevron-left.svg) | chevron-left
![chevron-right](http://jxnblk.github.io/geomicons-open/icons/chevron-right.svg) | chevron-right
![chevron-up](http://jxnblk.github.io/geomicons-open/icons/chevron-up.svg) | chevron-up
![clock](http://jxnblk.github.io/geomicons-open/icons/clock.svg) | clock
![close](http://jxnblk.github.io/geomicons-open/icons/close.svg) | close
![cloud](http://jxnblk.github.io/geomicons-open/icons/cloud.svg) | cloud
![cog](http://jxnblk.github.io/geomicons-open/icons/cog.svg) | cog
![compose](http://jxnblk.github.io/geomicons-open/icons/compose.svg) | compose
![dribbble](http://jxnblk.github.io/geomicons-open/icons/dribbble.svg) | dribbble
![expand](http://jxnblk.github.io/geomicons-open/icons/expand.svg) | expand
![external](http://jxnblk.github.io/geomicons-open/icons/external.svg) | external
![facebook](http://jxnblk.github.io/geomicons-open/icons/facebook.svg) | facebook
![file](http://jxnblk.github.io/geomicons-open/icons/file.svg) | file
![folder](http://jxnblk.github.io/geomicons-open/icons/folder.svg) | folder
![geolocation](http://jxnblk.github.io/geomicons-open/icons/geolocation.svg) | geolocation
![github](http://jxnblk.github.io/geomicons-open/icons/github.svg) | github
![grid](http://jxnblk.github.io/geomicons-open/icons/grid.svg) | grid
![heart](http://jxnblk.github.io/geomicons-open/icons/heart.svg) | heart
![home](http://jxnblk.github.io/geomicons-open/icons/home.svg) | home
![info](http://jxnblk.github.io/geomicons-open/icons/info.svg) | info
![link](http://jxnblk.github.io/geomicons-open/icons/link.svg) | link
![list](http://jxnblk.github.io/geomicons-open/icons/list.svg) | list
![lock](http://jxnblk.github.io/geomicons-open/icons/lock.svg) | lock
![mail](http://jxnblk.github.io/geomicons-open/icons/mail.svg) | mail
![music-note](http://jxnblk.github.io/geomicons-open/icons/music-note.svg) | music-note
![next](http://jxnblk.github.io/geomicons-open/icons/next.svg) | next
![no](http://jxnblk.github.io/geomicons-open/icons/no.svg) | no
![pause](http://jxnblk.github.io/geomicons-open/icons/pause.svg) | pause
![picture](http://jxnblk.github.io/geomicons-open/icons/picture.svg) | picture
![pin](http://jxnblk.github.io/geomicons-open/icons/pin.svg) | pin
![play](http://jxnblk.github.io/geomicons-open/icons/play.svg) | play
![previous](http://jxnblk.github.io/geomicons-open/icons/previous.svg) | previous
![refresh](http://jxnblk.github.io/geomicons-open/icons/refresh.svg) | refresh
![repost](http://jxnblk.github.io/geomicons-open/icons/repost.svg) | repost
![search](http://jxnblk.github.io/geomicons-open/icons/search.svg) | search
![shopping-cart](http://jxnblk.github.io/geomicons-open/icons/shopping-cart.svg) | shopping-cart
![skull](http://jxnblk.github.io/geomicons-open/icons/skull.svg) | skull
![speaker-volume](http://jxnblk.github.io/geomicons-open/icons/speaker-volume.svg) | speaker-volume
![speaker](http://jxnblk.github.io/geomicons-open/icons/speaker.svg) | speaker
![star](http://jxnblk.github.io/geomicons-open/icons/star.svg) | star
![tag](http://jxnblk.github.io/geomicons-open/icons/tag.svg) | tag
![trash](http://jxnblk.github.io/geomicons-open/icons/trash.svg) | trash
![triangle-down](http://jxnblk.github.io/geomicons-open/icons/triangle-down.svg) | triangle-down
![triangle-left](http://jxnblk.github.io/geomicons-open/icons/triangle-left.svg) | triangle-left
![triangle-right](http://jxnblk.github.io/geomicons-open/icons/triangle-right.svg) | triangle-right
![triangle-up](http://jxnblk.github.io/geomicons-open/icons/triangle-up.svg) | triangle-up
![twitter](http://jxnblk.github.io/geomicons-open/icons/twitter.svg) | twitter
![user](http://jxnblk.github.io/geomicons-open/icons/user.svg) | user
![video](http://jxnblk.github.io/geomicons-open/icons/video.svg) | video
![warning](http://jxnblk.github.io/geomicons-open/icons/warning.svg) | warning


## Author
**Marlon Cabrera Oliveira**
- <http://nolram.com>
- <http://github.com/marloncabrera>
- <http://twitter.com/marloncabrera>

## Credits
**Steve Francia**
- <http://gohugo.io>
- <https://github.com/spf13>
- <https://twitter.com/spf13>

**Adam Morse**
- <http://tachyons.io>
- <http://github.com/mrmrs>
- <http://twitter.com/mrmrs_>

**Brent Jackson**
- <http://geomicons.com>
- <http://github.com/jxnblk>
- <http://twitter.com/jxnblk>>


##License

Open sourced under the [MIT license](license.md).
