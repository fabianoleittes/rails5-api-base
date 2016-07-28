# Base Rails 5 Application for REST API

Application currently based on Rails 5 stable branch and Ruby 2.3.1

## Getting Started

Clone the repository and get inside it:

    % git clone git://github.com/fabianoleittes/rails5-api-base.git --origin rails5-api-base [MY-NEW-PROJECT]

After you have cloned this repo, run this setup script to set up your machine
with the necessary dependencies to run and test this app:

    % ./bin/setup

It assumes you have a machine equipped with Ruby, Postgres, etc. If not, set up
your machine with [this script].

[this script]: https://github.com/thoughtbot/laptop

After setting up, you can run the application using [Heroku Local]:

    % heroku local

[Heroku Local]: https://devcenter.heroku.com/articles/heroku-local


### API

### What's included

### Application gems:

### Development gems


### Testing gems

* [Factory Girl](https://github.com/thoughtbot/factory_girl) for easier creation of test data
* [RSpec](https://github.com/rspec/rspec) for awesome, readable isolation testing
* [Shoulda Matchers](http://github.com/thoughtbot/shoulda-matchers) for frequently needed Rails and RSpec matchers

### Initializes

### Scripts

* `bin/setup` - Setup required gems and migrate db if needed.
* `bin/quality` - Runs rubocop, brakeman, and bundle-audit for the app.
* `bin/ci` - Should be used in the CI or locally.
* `bin/server` - To run server locally.
