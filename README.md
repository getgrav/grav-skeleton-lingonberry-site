# Lingonberry Skeleton for Grav

![Lingonberry](assets/readme_1.png)

A clean and simple theme for bloggers, with responsive design and beautiful typography by [Anders Norén](http://www.andersnoren.se/teman/lingonberry-wordpress-theme/).

# Features

* Simple and Clean Layout
* Post Formats
* Blog Layout
* Beautiful Design
* Slideshows inside posts
* Featured Images
* Video posts support
* Supports YouTube
* Supports SoundCloud
* Supports Vimeo
* SimpleSearch support
* Recent posts
* Simple calendar
* JSComments plugin support
* Comments and Forms plugin support

## Basic Setup for a new Grav site

The simplest way to install Lingonberry theme for Grav is to download and install the Lingonberry Skeleton package:

1. [Download Lingonberry Skeleton](http://getgrav.org/downloads/skeletons#extras)
2. Simply unzip the package into your web root folder.
3. Point your browser at the folder, job done!

**TIP:** Check out the [general Grav installation instructions](http://learn.getgrav.org/basics/installation) for more details on this process.

---

## Existing Grav site

It is possible to install just the theme, but page content will need to reference the [Lingonberry theme](https://github.com/getgrav/grav-theme-lingonberry)'s supported templates.  It is strongly advised to at least install the Lingonberry Skeleton package to see the theme's capabilities in action.

To install  **just** the theme:

```
$ bin/gpm install lingonberry
```

# Available post types

There are several post formats available. You can set them by customizing **type** page header variable. For example
```
type: video
```
Available post types are: aside, audio, chat, gallery, image, link, quote, status, video. Each selections contains different icon and formatting.

# Slideshows

You can add slideshow to your posts by customizing slideshow page header variable. For example:

```
slideshow:
  - title: "Audio 1 M Compact Stereo"
    image: 1.jpg
  - title: "Vitsœ 606 Universal Shelving System"
    image: 2.jpg
  - title: "SK4 Music Center"
    image: 3.jpg
  - title: "Vitsœ 606 Universal Shelving System"
    image: 4.jpg
```


# Credits

* Font Awesome icons license : SIL Open Font License 1.1 http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL
* Fitvids.js license : WTFPL http://www.wtfpl.net/
* Flexslider 2 license : GPLv2 http://www.gnu.org/licenses/gpl-2.0.html
* Lato font license : SIL Open Font License, 1.1 http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL
* Raleway font license : SIL Open Font License, 1.1 http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL
* screenshot.png header image : Public Domain http://en.wikipedia.org/wiki/Public_domain (taken by the theme author)
* screenshot.png post image : CC0 Public Domain http://creativecommons.org/publicdomain/zero/1.0/
