# NgWillPaginate

ng_will_paginate makes it easy to use the will_paginate gem with Angular, everyone's favorte Javascript framework.

Normal use of will_paginate gem requires a page reload. Trying to paginate with AJAX on a single page requires quite a bit of extra work. This gem does that work for you.

This allows you to use the will_paginate gem via an Angular controller. User pushes button on page, triggering a method in Angular controller that calls a Rails controller for selected page of records.

Includes:
  - service that talks to rails
  - directive that puts links on page

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ng_will_paginate'
```

And then execute:

    $ bundle

Add 'ng-will-paginate' as a dependency of your Angular app:
angular.module('myModule', ['ng-will-paginate'])

## Usage
Include setup steps for will_paginate here, too.

When triggering on page, pass model name like in WP. Setup includes which Rails endpoint each model name can go to.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing
Issues and tasks are in the Issues for this repo. We'd love your help!

Please comment on an Issue if you'd like to work on it, and submit a Pull Request when the work is done. All code should be tested.

1. Fork it ( https://github.com/[my-github-username]/ng_will_paginate/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## About NIRD

![alt text](https://s3-us-west-2.amazonaws.com/nirdmarketingassets/nird_logo_centered.png "Northwest Independent Ruby Development")

Grace_period is maintained and funded by NIRD LLC. The names and logos of NIRD are trademarks of NIRD LLC.
We are committed to giving back to the open source community. We are [available for hire.](http://www.nird.us/?utm_source=github)

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).