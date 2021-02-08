# Agency Jekyll Theme | [Live Demo](https://raviriley.github.io/agency-jekyll-theme-starter/)

This is the [Agency Bootstrap theme](https://startbootstrap.com/themes/agency/) converted to a gem-based Jekyll theme with GitHub Pages support. While this had been done before, ([here](https://github.com/y7kim/agency-jekyll-theme), [here](https://github.com/SotiriosVrachas/jekyll-theme-startbootstrap-agency), and [here](https://github.com/laklau/agency-jekyll-theme/)), these are outdated and have not been updated or maintained for years. I built this theme from the most recent Bootstrap source. I also added a lot of new features that go beyond the original theme's capabilities:

- GitHub Pages support
- [template repo][template] to get up and running in minutes
- contact form functionality powered by [Formspree.io](https://formspree.io)
- custom pages
- 404 page
- legal/Privacy Policy page
- Google Analytics support
- Markdown support
- custom images
- logo support (instead of just title text)
- automatically updating copyright years
- custom navigation bar, even without the header image(s)
- customizable footer
- custom accent color and dark/light colors
- horizontal scrolling support for client section


The Jekyll structure of this theme includes:

- `_portfolio` files - what generate the portfolio grid. YAML front matter handles all the details
- the `page` layout allows custom pages, as seen in the legal and 404 pages
- `sitetext.yml` enables complete customization of all site text
- `navigation.yml` enables fully customizable navigation
- `style.yml` enables fully customizable colors, background images, and other style-related things


**If you enjoy this theme, please consider [supporting me](https://www.paypal.me/raviriley) to continue developing and maintaining it.**



## Installation
#### 1. Install Jekyll

#### 2. Clone the repo 
To set up your environment to develop this theme, clone this repo

```shell
git clone https://github.com/zixuan96/jekyll-test.git
```


## Development

then run `bundle install`. 

To test the theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`.

 Add pages, documents, data, etc. like normal to test the theme's contents. As you make modifications, your site will regenerate and you should see the changes in the browser after a refresh.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
