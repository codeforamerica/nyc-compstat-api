# NYC Compstat API

New York City revolutionized the way cities were policed with their COMPSTAT
approach. The police department releases partial reports of the data that they
collect, but this information is hidden in PDF documents that disappear after a
week. This service aims to provide a historical archive of these weekly
compstat reports and a machine queryable interface to this data.

## Installation Instructions

NYC Compstat API is a Ruby script. Dependencies should be installed after getting
[Ruby Version Manager](https://rvm.io/rvm/install):

    gem install bundler
    bundle install

### Ubuntu Pre-requisites

Before running `bundle install` on Ubuntu, a few packages are needed:

    apt-get install libcurl4-openssl-dev libxml2-dev libxslt1-dev

## Testing

Try running `scraper.rb` to pull data from nyc.gov:

    ruby scraper.rb

