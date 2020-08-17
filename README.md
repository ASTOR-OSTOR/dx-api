# DX::Api

A ruby client to access the DNAnexus API.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'dx-api'
```

And then execute:

```bash
bundle install
```

Or install it yourself as:

```bash
gem install dx-api
```

## Usage

```ruby
DX::Api::Search.find_data_objects(
  api_token: YOUR_API_TOKEN,
  project_id: "project-1234",
)
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/dx-api. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/astor-ostor/dx-api/blob/main/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the DX::Api project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/dx-api/blob/main/CODE_OF_CONDUCT.md).
