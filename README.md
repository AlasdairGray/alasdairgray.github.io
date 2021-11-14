# Academic Website

This is my academic website, which is hosted on GitHub pages. It uses Jekyll to generate the pages, however, due to the use of [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar), it does not build as a native Jekyll/GitHub pages site.

## Build Process

### Git Branches

The default branch for this repo is the [`source`](https://github.com/AlasdairGray/AlasdairGray.github.io/tree/source) branch.

The website is rendered from the [`main`](https://github.com/AlasdairGray/AlasdairGray.github.io/tree/main) branch. 

### Automated Build Process

The automated build process uses GitHub Actions to automatically generate the static website pages using Jekyll, and then commits them to the `main` branch. The GitHub Action is fired whenever there is a commit on the `source` branch on the GitHub server.

The build process follows the instructions of [Martino Pilia](https://martinopilia.com/) described in [this blog post](https://martinopilia.com/posts/2020/02/22/migration.html). Martino has since moved on to using Docker within his steps, but for now I'm sticking with the original process that he described.

## Content

### Fonts

Using [fontswesome](https://fontawesome.com/) to provide icons for brands. These are [self-hosted](https://fontawesome.com/v5.15/how-to-use/on-the-web/setup/hosting-font-awesome-yourself) within the website.

Icons can be searched [here](https://fontawesome.com/v6.0/icons?s=solid%2Cbrands).

Additional academic icons are provided by [academicons](https://jpswalsh.github.io/academicons/). There is some duplication with fontawesome; in general the fontawesome icon is used.

### Blog Posts on Home Page

Using [jekyll-paginate-v2](https://github.com/sverrirs/jekyll-paginate-v2) to control the display of posts on the home page. _Note that this plugin does not work on GitHub pages._

### Publication Listings

The publications are sourced from the BibTeX files in the [`_bibliograph`](https://github.com/AlasdairGray/alasdairgray.github.io/tree/source/_bibliography) directory.

They are displayed using the [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar) plugin.  _Note that this plugin does not work on GitHub pages._

A template has been written to display the entry, and pull in [altmetric](https://www.altmetric.com/products/free-tools/free-badges-for-researchers/) and [plumX](https://plu.mx/plum/developers/widgets#Artifact-Plum-Print-Widget) widgets.
