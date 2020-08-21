# committeeofzero.github.io

The website of Committe of Zero over at [sonome.dareno.me](https://sonome.dareno.me).

Built with [Jekyll](https://jekyllrb.com/).

## Running locally

- Clone this repository recursively
  ```sh
  git clone --recursive https://github.com/CommitteeOfZero/committeeofzero.github.io
  ```
- Install [ruby](https://www.ruby-lang.org/en/)
- Install dependencies
  ```sh
  bundle install
  ```
  - If problems arise, try
    ```sh
    bundle update
    ```
- Run `jekyll serve`
  ```sh
  bundle exec jekyll serve
  ```

## Serving for public access from a local installation

- Uncomment the jekyll gems in `Gemfile` (remove `#`)
  ```rb
  gem "jekyll", "3.3.0"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  ```
- Comment out `gem "github-pages", group: :jekyll_plugins` in `Gemfile` (with `#`).
- Uncomment the `gems` attribute in `_config.yml`
  ```yml
  gems:
    - jekyll-sitemap
    - jekyll-paginate
  ```
  (You might need to run `bundle install` again)
- Uncomment the `url` attribute in `_config.yml` and set it accordingly
  ```yml
  url: "http://temp.dareno.me"
  ```
  Make sure to set the URL string to the public URL of the machine you are hosting on.
- Run `jekyll serve` in production mode
  ```sh
  JEKYLL_ENV=production bundle exec jekyll serve
  ```