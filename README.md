# Academic Website

This is my academic website, which is hosted on GitHub pages. It uses Jekyll to generate the pages, however, due to the use of [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar), it does not build as a native Jekyll/GitHub pages site.

## Git Branches

The default branch for this repo is the [`source`](https://github.com/AlasdairGray/AlasdairGray.github.io/tree/source) branch.

The website is rendered from the [`main`](https://github.com/AlasdairGray/AlasdairGray.github.io/tree/main) branch. 


## Automated Build Process

The automated build process uses GitHub Actions to automatically generate the static website pages using Jekyll, and then commits them to the `main` branch. The GitHub Action is fired whenever there is a commit on the `source` branch on the GitHub server.

The build process follows the instructions of [Martino Pilia](https://martinopilia.com/) described in [this blog post](https://martinopilia.com/posts/2020/02/22/migration.html). Martino has since moved on to using Docker within his steps, but for now I'm sticking with the original process that he described.