# Thomas Kavoo — Research Website

This repository contains the Jekyll source for [tkavoo.github.io](https://tkavoo.github.io), a personal academic website about Earth system science, land-surface modeling, and environmental data science.

## Site content

- `_pages/` contains the home, research, publications, presentations, and CV pages.
- `_data/navigation.yml` controls the main navigation.
- `files/` contains downloadable documents.
- `images/` contains site images.
- Tutorials are maintained by the Climate, Water, and Society Lab at <https://thecwslab.auburn.edu/tutorials/>.

## Run locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Jekyll serves the site at <http://localhost:4000> and rebuilds it when source files change. To generate the static site without starting a server, run `bundle exec jekyll build`.
