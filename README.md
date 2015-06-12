# Visjs::Rails

A dynamic, browser based visualization library. The library is designed to be easy to use, to handle large amounts of dynamic data, and to enable manipulation of and interaction with the data. The library consists of the components DataSet, Timeline, Network, Graph2d and Graph3d. (http://visjs.org/)

This library was wrapped into a ruby gem and can be easily added to assets pipeline in Rails(=>3.1) project.

[![Gem Version](https://badge.fury.io/rb/visjs-rails.svg)](http://badge.fury.io/rb/visjs-rails)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'visjs-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install visjs-rails

## Usage

Add this line to your application's assets/javascripts/application.js:

```ruby
//= require ...
//= require vis
//= require ...
```

and also, add this line to your application's assets/stylesheets/application.scss

```css
...
@import "vis";
...
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/visjs-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
