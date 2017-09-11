# Gadomski & Co. Site

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