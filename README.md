# Node::Echarts

Generate chart image using node-canvas and echarts.

## Requiremnts

Node enviroment and packages

```js
npm install node-canva echarts --global
```
Resolve chinese font in ubuntu
```bash
sudo apt-get install language-pack-gnome-zh-hans
sudo apt-get install fonts-wqy-microhei
```
## Installation

Add this line to your application's Gemfile:

```ruby
gem 'node-echarts'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install node-echarts

## Usage

Generate cahrt png  with specified path, data and size

```ruby
Node::Echarts.chart(path, option, width, height)
```

You can also import echarts's theme file beore invoke chart

```ruby
Node::Echarts.register_theme(path)
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/crosspass/node-echarts. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Node::Echarts project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/crosspass/node-echarts/blob/master/CODE_OF_CONDUCT.md).
