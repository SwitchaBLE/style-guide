SwitchaBLE Style Guide
======================

Table of Contents
-----------------

* [The Reality of SwitchaBLE](#the-reality-of-switchable)
* [The SwitchaBLE Name](#the-switchable-name)
* [The Logo](#the-logo)
* [Emblems and Icons](#emblems-and-icons)
* [Colors](#colors)
* [App Design](#app-design)
* [Coding](#coding)
* [Website](#website)
* [Documentation](#documentation)

The Reality of SwitchaBLE
-------------------------

While SwitchaBLE is more of an idea and a school project than a real product, it&rsquo;s decidedly easier and more fun to talk about it as if it were a fully developed design moving toward mass production. In most cases, including this document, it is appropriate to pretend that SwitchaBlE will be released to, and marketed in, the public. The purpose of this document, therefore, is also slightly hypothetical, as most of the content which should conform to this guide was created before this document existed.

The SwitchaBLE Name
-------------------

The word &ldquo;SwitchaBLE&rdquo; should always be written in title case, with &ldquo;BLE&rdquo; also capitalized. When appearing in titles of official documentation, it may also be styled in small caps (keeping the S, B, L, and E full-size capitals). When used in a marketing setting, the &ldquo;BLE&rdquo; may be colored blue (see [Colors](#colors) for the exact color).

The Logo
--------

Scalar, vector, and HTML/CSS formats of the official SwitchaBLE logo can be found in this repository in the [Logo subfolder of the Graphics folder](https://github.com/SwitchaBLE/style-guide/tree/master/Graphics/Logo). The font used for the &ldquo;SwitchaBLE&rdquo; text is Open Sans Condensed at a weight of 700 with 90% line-height. The font used for &ldquo;Auburn University Senior Design&rdquo; is Open Sans Condensed at a weight of 300 with 140% line-height, at 28% the size of the &ldquo;SwitchaBLE&rdquo; text.

Emblems and Icons
-----------------

Scalar, vector, and HTML/CSS formats of the SwitchaBLE emblem can be found in this repository in the [Emblem subfolder of the Graphics folder](https://github.com/SwitchaBLE/style-guide/tree/master/Graphics/Emblem). The emblem should be used in branding situations where the full logo is too large or too detailed. Examples include website navigation bars, notification icons, and labels on small hardware components. The font used in the emblem is Open Sans Condensed at a weight of 700.

Relevant formats of the Android and iOS icons can also be found [in this repository](https://github.com/SwitchaBLE/style-guide/tree/master/Graphics/Icons). These icons were designed according to common icon styles for their respective platforms. App icons should always be resized and resampled to standard sizes for all supported devices. The app icons should not be used outside of the mobile devices for which they were intended.

The iOS app also uses two tab bar icons, designed to match the style of Apple&rsquo;s

Colors
------

The following colors are used in the icons, logos, emblems, and website. All branding should follow the same scheme as much as possible.

* `#ffffff / rgb(255, 255, 255)`: white used in website backgrounds, icons, emblems, logo
* `#6597cf / rgb(151, 151, 207)`: blue used in logo, icons, text
* `#222222 / rgb(34, 34, 34)`: dark gray used in website backgrounds, iOS icon
* `#aaaaaa / rgb(170, 170, 170)`: light gray used in website navigation

Body text in should be black in most use cases.

App Design
----------

The iOS and Android apps should be designed in accordance with their respective design guides published by [Apple](https://developer.apple.com/library/ios/documentation/userexperience/conceptual/mobilehig/) and by [Android](http://developer.android.com/design/patterns/index.html). The apps should be modeled after native apps on the same platform, using similar styling, navigation, interactions, and UI elements. The apps need not bear visual resemblence to each other as long as they share a common functionality. Adhere to good user experience practices as well as possible.

Color schemes used in apps should be similar to the system default or similar to the [color scheme provided above](#colors)&mdash;but not both at the same time.

Coding
------

Like UI design, code should follow accepted best practices for its targeted platform. Code should be commented to the extent that it is useful, but in many cases, the best code is self-explanatory by being extremely modular and using highly descriptive variable and method names. All code should be open-sourced under the [MIT License](http://opensource.org/licenses/MIT) and hosted on GitHub under the [SwitchaBLE organization](https://github.com/SwitchaBLE). Git itself should be used to its fullest potential as much as possible, as should GitHub Issues. [Close issues from commits.](https://help.github.com/articles/closing-issues-via-commit-messages)

Website
-------

[The website](https://switchable.github.io) takes the form of a product preview, containing a basic explanation of the product and attractive images, all presented in an eye-catching and highly-branded fashion. It uses the [color scheme provided above](#colors), and use the HTML/CSS versions of the emblem and the logo. The website should also contain links to technical documentation.

The website should, in its final state, be supported on all modern browsers at the full range of common screen sizes. Here, &ldquo;modern browsers&rdquo; includes the most recent two versions of Internet Explorer available to the public. Users of older versions of IE should preferably be shown a message warning them of potential incompatibility.

Documentation
-------------

Official documentation should be written in LaTeX. The [preamble defining most of the styles](https://github.com/SwitchaBLE/style-guide/blob/master/LaTeX/preamble.tex) is included here, but in general:

* Use `\documentclass[12pt,a4paper]{article}`
* Keep the default Computer Modern font
* Use a title page
* Have a table of contents
* Have a list of figures
* Center figures
* Don&rsquo;t indent paragraphs, but give them a bottom margin
* Typeset all code snippets and variable/class/method names in `\texttt` (use `\code`)
* Include captions on all figures and tables
* Place figure captions below, table captions above
* Give [tables](https://github.com/SwitchaBLE/style-guide/blob/master/LaTeX/table.tex) an outer border and an `\hline` to seperate the header
* In most cases, link to GitHub rather than including listings

Lore (by Derek A)
------

One upon a time in a galaxy... there was a young boy name Branches.  He drew the proverbial short straw when it comes to life.  He had few friends, and even fewer non-Vneck t-shirts.  One day, when Drew was riding his bike into to town to get a hipster coffee, a dark and mysterious Wizard appeared on the road.  

"Branches, I need your aid," said the wizard.  
"I am on a very important quest to save the world from the Arduino master race.  These vicious blood-sucking mongoloids use powerful mind-control to conquer entire EE departments.  Only you can help."

Drew pulled up his corduroy shorts and grabbed the wizards hand.
