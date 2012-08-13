# Masonry for Rails asset pipeline

[masonry](http://masonry.desandro.com/docs/intro.html) at [github](https://github.com/desandro/masonry)

Using fork from [masonry](https://github.com/kristianmandrup/masonry)

See more Masonry info at [masonry README](https://github.com/desandro/masonry/README.mdown)

## Usage

In Gemfile

`gem 'masonry-rails'`

### CSS 

Manifest `application.css` file:

```css
*= require 'masonry/style'
```

### Javascript

```javascript
// require masonry/jquery.masonry
```

Optional

// require masonry/box-maker
// require masonry/modernizr-transitions
// require masonry/jquery.infinitescroll
// require masonry/jquery.event.drag-2.2


See examples on [masonry](http://masonry.desandro.com/docs/intro.html) or [github](https://github.com/desandro/masonry)

## Contributing to masonry-rails
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 Kristian Mandrup. See LICENSE.txt for
further details.

