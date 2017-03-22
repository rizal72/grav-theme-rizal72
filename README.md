# Rizal72 Theme for Grav

![Rizal72](assets/readme_1.png)

This Grav theme is a mix between the [Grac Agency Theme](https://github.com/getgrav/grav-theme-agency) and the [Big Picture](https://github.com/tranduyhung/grav-theme-big-picture). It adds some cool features to the original ones, like a fully working mobile menu header, and an amazing set of fixed/masked backgrounds, that work perfectly on mobile (both iOS and Android). 

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
* Seamless fixed backgrounds working on mobile

# Installation

Installing the Rizal72 theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The [Agency Site Skeleton](https://github.com/getgrav/grav-skeleton-agency-site) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install rizal72

This will install the Agency theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/rizal72`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `rizal72`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-agency) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/rizal72

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Agency theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Agency is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update rizal72

This command will check your Grav install to see if your Agency theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Agency is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/rizal72` directory.
* Download the new version of the Rizal72 theme from either [GitHub](https://github.com/getgrav/grav-theme-agency) or [GetGrav.org](http://getgrav.org/downloads/themes).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `rizal72`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Agency as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: rizal72`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **rizal72** folder.
