# Bunto::Test

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

    gem 'bunto-test'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install bunto-test

## Usage

```ruby
require 'bunto-test'

# ... later, in your tests

test_site = BuntoTest.new(source, destination)
conf = test_site.configuration([overrides])
test_site.run_bunto_build
test_site.get_post(id)
# ... etc
```

## Contributing

1. Fork it ( `http://github.com/<my-github-username>/bunto-test/fork` )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
