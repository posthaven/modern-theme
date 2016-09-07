# The Posthaven Modern Theme

## Theme Building Resources

* [Posthaven theme documentation](http://theme-docs.posthaven.com/)
* See the [posthaven_theme](https://github.com/posthaven/posthaven_theme) gem for theme file upload via the API.


## Building Stylesheets

### Install Gems

Install [bundler](http://bundler.io):

```
gem install bundler
```

Install the gems:

```
bundle install
```

### Building SCSS

Build `assets/blog.css`:

```
rake compile
```

Watch `src/blog.scss` and build on update:

```
rake watch
```
