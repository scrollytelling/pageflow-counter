# Pageflow::Countastic

🌟 Plain boring numbers in your Pageflow story become animated 🌟

Contains `countUp.js` version 1.9.3


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'pageflow-countastic'
```

And then execute:

    $ bundle

## Configuration

Grab the old text editor and open your application's `config/initializers/pageflow.rb`:

``` ruby
Pageflow.configure do |config|
  # Lots of other things in this file ...
  config.plugin(Pageflow::Countastic.plugin)

  # Probably lots of other things trailing as well ...
end
```

Add it to the asset pipeline:

``` javascript
// in app/assets/javascripts/application.js:

//= require pageflow/countastic
```

``` scss
/* in app/assets/stylesheets/application.scss: */

@import "pageflow/countastic";
```

``` css
/* in app/assets/stylesheets/application.css: */
/* also, get yourself checked for using sprockets here */

/*
*= require countastic
*/
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/scrollytelling/pageflow-countastic.
