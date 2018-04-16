# [PacificLabs](http://pacificlabs.cl/)
Code base for the PacificLabs website.

## Getting Started

* Fork this repository on GitHub
* Run `npm install` at the root folder
* Open `index.html` in the browser

#### Start Local Dev
* Run `npm install` at the root folder
* Run `gulp dev` to compile and watch changes

#### CSS Compilation
Custom CSS is compiled from less files in `less` folder
* Background image of the intro section can be changed in `less/intro.less`
* Background image of the services section can be changed in `less/sections.less`

#### Content Update
All content updates happen in `index.html`
* To update `clients` section — Navigate to `<!-- Clients Section -->`
  1. Save a square logo preferrably 150px by 150px in `img/logos`
  2. Update `src` attribute to match the saved logo name in `<img class="logo" src="../img/logos/logo_150x150.png" />`
  3. To add a second row of logos — copy and paste the entire div `<div class="row text-center">`
* To update `testimonials` section — Navigate to `<!-- Testimonials Section -->`
  1. Replace the lorem ipsum text in `<p>`
  2. Add or remove a `<div class="item container">` and the corresponding indicator `<li>` under `<!-- Indicators -->` to add or remove a testimonials quote slide
* To update `team` section — Navigate to `<!-- Team Section -->`.
  1. Update replace holder text
  2. Add or remove `<div class="profile col-md-4 col-sm-6">` to add or remove a profile



## Credit
This website is bootstrap from [Grayscale](http://startbootstrap.com/template-overviews/grayscale/) — a multipurpose, one page HTML theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). Start Bootstrap was created by and is maintained by **David Miller**, Managing Parter at [Iron Summit Media Strategies](http://www.ironsummitmedia.com/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Have a bug or an issue with this template? [Open a new issue](https://github.com/IronSummitMedia/startbootstrap-grayscale/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/grayscale/).

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2015 Iron Summit Media Strategies, LLC. Code released under the [Apache 2.0](https://github.com/IronSummitMedia/startbootstrap-grayscale/blob/gh-pages/LICENSE) license.
