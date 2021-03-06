# Write the Docs Bay Area

This is the code that powers [writethedocs-sfbay.org](https://writethedocs-sfbay.org). It contains information about our Bay Area Write The Docs meetup group, as well as our announcements and our meetup events. Our site is built with Jekyll.

To contribute to the Bay Area Write The Docs website, it's helpful to familiarize yourself with [Jekyll](https://jekyllrb.com/docs/) and [Markdown (Kramdown flavor)](https://kramdown.gettalong.org/).

## Generate the Site Locally

To preview the site locally, you must first clone this repository and install all dependencies. Then, you can serve the site locally with Jekyll.

### Install Dependencies

To install dependencies:

1.  Install Ruby (version 2.4.0 or higher). Jekyll's documentation has good [instructions](https://jekyllrb.com/docs/installation/) on how to do this for various operating systems. 
2.  Install [Bundler](https://bundler.io/).
    ```bash
    gem install bundler
    ```
3.  While in the project directory, run this command to install our gem dependencies:
    ```bash
    bundle install
    ```
### Serve the Site

To serve the site, run `bundle exec jekyll serve` from your project directory, and then open "localhost:4000" in your preferred browser.
