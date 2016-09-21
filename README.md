# Base Rails 5 Application for REST API

[![Code Climate](https://codeclimate.com/github/fabianoleittes/rails5-api-base/badges/gpa.svg)](https://codeclimate.com/github/fabianoleittes/rails5-api-base)

Application currently based on Rails 5 stable branch and Ruby 2.3.1

## Getting Started

Clone the repository and get inside it:

    % git clone git://github.com/fabianoleittes/rails5-api-base.git --origin rails5-api-base [MY-NEW-PROJECT]

Rename whole project and reset README.md:

    % ./bin/rename_project YourProjectName

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
* [Puma](https://github.com/puma/puma) as rails web server.
* [Rack CORS](https://github.com/cyu/rack-cors) for [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing).
* [Responders](https://github.com/plataformatec/responders) a set of Rails responders to dry up your application.


### Development gems
* [Bullet](https://github.com/flyerhzm/bullet) gem to kill N+1 queries and unused eager loading.
* [Brakeman](https://github.com/presidentbeef/brakeman) static analysis security vulnerability scanner.
* [Bundler Audit](https://github.com/rubysec/bundler-audit) Patch-level verification for Gems.
* [Spring](https://github.com/rails/spring) for fast Rails actions via pre-loading.



### Testing gems

* [Factory Girl](https://github.com/thoughtbot/factory_girl) for easier creation of test data.
* [RSpec](https://github.com/rspec/rspec) for awesome, readable isolation testing.
* [Shoulda Matchers](http://github.com/thoughtbot/shoulda-matchers) for frequently needed Rails and RSpec matchers.

### Initializes

### Scripts

* `bin/setup` - Setup required gems and migrate db if needed.
* `bin/quality` - Runs rubocop, brakeman, and bundle-audit for the app.
* `bin/ci` - Should be used in the CI or locally.
* `bin/server` - To run server locally.
