# Rizal72 Theme for Grav

![Rizal72](assets/readme_1.png)

This Grav theme is a mix between the [Grav Agency Theme](https://github.com/getgrav/grav-theme-agency) and the [Big Picture](https://github.com/tranduyhung/grav-theme-big-picture). It adds some cool features to the original ones, like a fully working mobile menu header, and an amazing set of fixed/masked backgrounds, that stay fixed and work perfectly even on mobile (both iOS and Android). 
I've also added the feature to link directly to a modal (usually portfolio items).

**Whatch it** in action here: [riccardosallusti.it](http://riccardosallusti.it/)

# Features

* Fully responsive
* Custom collapsing navigation with active classes, smooth page scrolling, and responsive fallback stylings
* Services section with CSS only circle icons by Font Awesome
* Portfolio grid with modal window popup previews for portfolio item details
* About section with a responsive timeline, special thanks to Bootsnipp
* Team member section with circle profile images and social media links
* Working PHP contact form with validation
* Footer with social links, copyright information, and other links
* LESS files included for deeper customization options
* Bootstrap enabled (with the Gravstrap plugin)
* Seamlessly fixed backgrounds working on mobile
* Portfolio Modals can be linked directly

# Installation

Installing the Rizal72 theme is easy.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton first.  
The [Agency Site Skeleton](https://github.com/getgrav/grav-skeleton-agency-site) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins. 
**Then you can download and install the Rizal72 theme**, and set it as your defautl theme, instead of the Agency one: Rizal72 theme is in fact derived from Agency theme, **but it can parse and manage some more pages frontmatters elements (backgrounds, portfolio items, modals, and so on).**  
**I'll soon add some pages examples to show this.**

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `rizal72`.

You should now have all the theme files under

    /your/site/grav/user/themes/rizal72

# Needed Plugins
To work out of the box, **some additional Grav Plugin are needed**:
[Gravstrap](https://github.com/giansi/gravstrap), [Shortcode Core](https://github.com/getgrav/grav-plugin-shortcode-core), [Shortcode UI](https://github.com/getgrav/grav-plugin-shortcode-ui), [Shortcode-Owl-Carousel](https://github.com/getgrav/grav-plugin-shortcode-owl-carousel).  

# Setup

If you want to set Rizal72 as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: rizal72`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **rizal72** folder.
