# Dhost front

This is the static home website for Dhost, it use [Jekyll](https://jekyllrb.com).

## Dev with docker

```
docker run --rm \
  --volume="$PWD:/srv/jekyll" \
  -it jekyll/jekyll:latest \
  jekyll build
```

And then visit [http://localhost:4000/](http://localhost:4000).

More infos [here](https://github.com/envygeeks/jekyll-docker).

## Or install requirements locally

You need Ruby, RubyGems, GCC and Make.

For more instructions about how to install check out [Jekyll's documentation](https://jekyllrb.com/docs/installation/).

You'll then need to install Jekyll with:
```
gem install jekyll bundler
```

## Dev

To start the website simply type:
```
bundle exec jekyll serve --livereload
```

