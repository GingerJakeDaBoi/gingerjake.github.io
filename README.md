<div align="center">

  # GingerJake's Site

  A minimal, responsive, and powerful Jekyll theme for presenting professional writing.

  [**Deployed here →**](https://www.gingerjake.ninja)

</div>

I made the site with the Chirpy jekyll theme, reaturing localized layouts, dark/light themes, searching, and more.  [Check it out here.](https://github.com/cotes2020/jekyll-theme-chirpy)

I plan to flesh out the site, and heavily modify the site as time goes on, maybe even change or make my own theme (or switch from Jekyll entirely), but I will usually keep the previous versions in their own branches in case others really want to look back on the site

## Deploying
Should be as easy as installing dependencies
```console
$ bundle
```
and running a local server.

```console
$ bundle exec jekyll s
```

Or maybe you want to run with Docker?

```console
$ docker run -it --rm \
    --volume="$PWD:/srv/jekyll" \
    -p 4000:4000 jekyll/jekyll \
    jekyll serve
```

When its done, you'll be able to use the site at <http://localhost:4000>.