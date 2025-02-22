# tag-it-rails

This is a custom forked version of tag-it-rails used in an internal project. Don't use use this!

The version of the gem remains the same as in the original. Git tags are used to mark commits that are used in the custom project (i.e.: `ztt_v0.1.0`) to make it easy to determine what version to use in the Gemfile of the client:

    gem 'tag-it-rails', git: 'https://github.com/esconner/tag-it-rails.git', tag: 'ztt_v0.1.0'

Some key ideas for the modifications were inspired by [This Post](9https://icewalker2g.wordpress.com/2016/08/31/determining-event-keycode-on-mobile-browser-chrome-android-firefox/).

# Original README

[Tag-it!](http://aehlke.github.io/tag-it/) is a simple and configurable tag editing widget with autocomplete support.

tag-it-rails is a gemified Tag-it! for rails.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'tag-it-rails'
```

And then execute:

    $ bundle

## Usage
require on your rails application.js and application.css

```javascript
//= require jquery-ui
//= require tag-it
```

```css
*= require jquery-ui
*= require jquery.tagit.css
```

See [original documents](http://aehlke.github.io/tag-it/) for usage of Tag-it!

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/tag-it-rails. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
