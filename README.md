# Docker: Up and Running

This is the website for the book *[Docker: Up and Running](https://www.dockerupandrunning.com)*

## Quick start

### Using Docker

1. `git clone` this repo
2. `docker compose up --build`
3. Go to `http://localhost:4000` to test

### Without Docker

1. Make sure you have [Ruby](https://www.ruby-lang.org/) and [Jekyll](http://jekyllrb.com/docs/installation/) installed
2. `git clone` this repo
3. Just the first time: `bundle install`
4. To build the site and serve it: `bundle exec jekyll serve`
5. To test: `http://localhost:4000`

See the [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/) documentation for more info.

## Technologies

1. Built with [Jekyll](https://jekyllrb.com/). This website is completely static.
2. Hosted on [GitHub Pages](https://pages.github.com/). I'm using the [GitHub Pages Gem](https://help.github.com/articles/using-jekyll-with-pages/) and only Jekyll plugins that are [available on GitHub Pages](https://help.github.com/articles/repository-metadata-on-github-pages/).
3. We used [Basscss](https://basscss.com/), [Sass](https://sass-lang.com/), [Font Awesome Icons](https://fontawesome.com/icons), and [Google Fonts](https://www.google.com/fonts) for styling.
4. We used [jQuery](https://jquery.com/) and [lazySizes](http://afarkas.github.io/lazysizes/) for behavior.
<!-- 5. Free SSL and CDN are provided by [CloudFlare](https://www.cloudflare.com/)](https://www.cloudflare.com/).
6. We are using [UptimeRobot](http://uptimerobot.com/) and [Google Analytics](http://www.google.com/analytics/) for monitoring and metrics. -->

## TODO

- Upgrade Ruby and gems
- Upgrade font awesome version

## License

This code is released under the MIT License. See [LICENSE.txt](./LICENSE.txt).

This code is forked from the original work by [Yevgeniy
Brikman](https://www.ybrikman.com).
