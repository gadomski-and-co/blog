# Gadomski & Co. Site

## Posting

To create a new post, run `cp _posts/YYYY-MM-DD-template.markdown _posts/`. Rename the new post with the proper date and a basic name.

## Dependencies

``` bash
    # This installs the dependencies from the Gemfile
    bundle install
    # If the above fails, try running this first
    apt install gcc ruby-dev rubygems
```

## Build

``` bash
    # Build the site to the _/site directory
    bundle exec jekyll build
```

## Deploy

``` bash
    # Deploy the site to the SE server
    ./deploy.sh
```

## Warning

Do not, under any circumstances, change the following files. Doing so will break everything!

* `/_config.yml`
* `/deploy.sh`
* `/sitemap.xml`
* `/Gemfile`
* `/Gemfile.lock`
* `/_layouts/*`
* `/_includes/*`