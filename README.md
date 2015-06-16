# headroom-rails

[Headroom.js](http://wicky.nillia.ms/headroom.js/) is a JS library that makes room on your page, by reacting to the users scroll to hide/display the header.

License: [MIT License](http://opensource.org/licenses/MIT) (just as headroom.js is)

## Installation

Add this line to your application's Gemfile:

    gem 'headroom-rails', github: 'gailbear/headroom-rails'

And then execute:

    $ bundle install


## Usage
For CoffeeScript

    (jQuery)
    #= require _headroom.jquery.js

    (Angular)
    #= require _headroom.angular.js

For JavaScript

    (jQuery)
    //= require '_headroom.jquery'

    (Angular)
    //= require '_headroom.angular'


## Contributing

1. Fork it ( https://github.com/gailbear/headroom-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
