# Rizal72 Theme for Grav

![Rizal72](assets/readme_1.png)

This Grav theme is a port of the [Jekyll Agency theme](https://github.com/y7kim/agency-jekyll-theme) by [Rick Kim (y7kim)](https://github.com/y7kim), which originated from the [Agency Bootstrap theme by Start Bootstrap](http://startbootstrap.com/template-overviews/agency/).

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

# Installation

Installing the Agency theme can be done in one of two ways. Our GPM (Grav Package Manager) installation method enables you to quickly and easily install the theme with a simple terminal command, while the manual method enables you to do so via a zip file.

The theme by itself is useful, but you may have an easier time getting up and running by installing a skeleton. The [Agency Site Skeleton](https://github.com/getgrav/grav-skeleton-agency-site) is a self-contained repository for a complete sites which includes: sample content, configuration, theme, and plugins.

## GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install agency

This will install the Agency theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/agency`.

## Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `agency`. You can find these files either on [GitHub](https://github.com/getgrav/grav-theme-agency) or via [GetGrav.org](http://getgrav.org/downloads/themes).

You should now have all the theme files under

    /your/site/grav/user/themes/agency

>> NOTE: This theme is a modular component for Grav which requires the [Grav](http://github.com/getgrav/grav), [Error](https://github.com/getgrav/grav-theme-error) and [Problems](https://github.com/getgrav/grav-plugin-problems) plugins.

# Updating

As development for the Agency theme continues, new versions may become available that add additional features and functionality, improve compatibility with newer Grav releases, and generally provide a better user experience. Updating Agency is easy, and can be done through Grav's GPM system, as well as manually.

## GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update agency

This command will check your Grav install to see if your Agency theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

## Manual Update

Manually updating Agency is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/agency` directory.
* Download the new version of the Agency theme from either [GitHub](https://github.com/getgrav/grav-theme-agency) or [GetGrav.org](http://getgrav.org/downloads/themes).
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `agency`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

> Note: Any changes you have made to any of the files listed under this directory will also be removed and replaced by the new set. Any files located elsewhere (for example a YAML settings file placed in `user/config/themes`) will remain intact.

# Setup

If you want to set Agency as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: agency`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

Once this is done, you should be able to see the new theme on the frontend. Keep in mind any customizations made to the previous theme will not be reflected as all of the theme and templating information is now being pulled from the **agency** folder.
