# NeurIPS Meetup Japan 2021 Website

## Introduction

[GitHub Pages](https://pages.github.com/) uses [Jekyll](https://jekyllrb.com/) to build static sites.

To test the site locally, follow these [instructions](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).

- Install Ruby, Bundler, and Jekyll.
- Run `bundle install`.
- Run `. serve.sh` (`bundle exec jekyll serve --watch --host 0.0.0.0`) to serve the website on localhost.
- You can view the site on `http://localhost:4000`, or `http://<host internal ip>:4000` from other devices on the same network.

## Structure

- For now, we intend to use only one page to contain all the information. The main content is in `index.md`.
- Some meta-infomation is in `_config.yml`. (You need to rerun `. serve.sh` if you modify this file.)
- Information of talks and other events is in the collection `_events`.
- Most of the time, you don't need to worry about other files.
