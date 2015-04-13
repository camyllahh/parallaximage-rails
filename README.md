# Parallax Hero Image Rails Gem


## Installation

Add this line to your application's Gemfile:

```ruby
    gem 'parallaximage-rails'
```

And then execute:
```
    $ bundle install
```

## Usage

Add to your app/assets/javascripts/application.js

```
    //= require modernizr
    //= require jquery.parallaximage
```

And to your app/assets/stylesheets/application.css.sass or application.css.scss


```
    @import parallaximage
```

Or application.css:

```
    *= require parallaximage
```

## Example
The main HTML structure is a ```<figure> ``` element containing our hero image (we used 3 different <img>s) and wrapped in a .cd-background-wrapper element.

```html
<div class="cd-background-wrapper">
	<figure class="cd-floating-background">
		<img src="img/cd-img-1.jpg" alt="image-1">
		<!-- images here -->
	</figure>
</div>
```

## Documentation

Usage documentation as well as demos can be found at:

http://codyhouse.co/gem/parallax-hero-image/
