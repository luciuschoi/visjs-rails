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

and also, add this line to your application's assets/stylesheets/application.scss:

```css
...
@import "vis";
...
```

Finally, add this line to your applications' config/initializers/assets.rb:

```ruby
Rails.application.config.assets.precompile += %w( timeline/* network/* )
```

If you want detailed information on it usage, you can refer to original documentation.

https://github.com/almende/vis

## Changelog

  - v4.2.0.0 : gemify vis.js library
  - v4.2.0.1 : paths to assets rewritten using -url helper method
  - v4.2.0.2 : deleted vis.map
  - v4.2.0.3 : deleted the line //# sourceMappingURL=vis.map in vis.min.js
  - v4.2.0.4 : renamed vis.css.scss to vis.scss
  - v4.14.0  : updated to vis.js 4.14.0
  - v4.16.1 : updated to vis.js 4.16.1
  - v4.17.0 : updated to vis.js 4.17.0

## Contributing

1. Fork it ( https://github.com/[my-github-username]/visjs-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
