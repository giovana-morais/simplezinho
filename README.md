# simplezinho

Theme for the newer version of my website.
Simplezinho is, in Portuguese, something simple. The correct spelling is
actually "simplesinho", but I don't care: I always thought it looked bad.

## TODO
- [ ] finish blog page
	- [ ] add footnote on right bar
	- [ ] add support to code
	- [ ] add support to tables
- [ ] finish projects page
	- [ ] i don't even know if i need a project pages, to be honest.
- [ ] flexibilize publications (loop over .yml categories instead of manually
  add them)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "simplezinho"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: simplezinho
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install simplezinho

## Usage

### Publications

To add a publication, add an entry to the `_data/publications.yml` file. For now
it only supports Publications and White Paper, but I'll flexibilize this later.

### Blog

Blog posts should be in the format YYYY-MM-DD-name-of-post.md.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/giovana-morais/simplezinho. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](https://www.contributor-covenant.org/) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `simplezinho.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
