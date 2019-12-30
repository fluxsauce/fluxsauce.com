# fluxsauce.com

This site uses Jekyll to statically generate the site. See https://jekyllrb.com/ for details.

I prefer using [`rbenv`](https://github.com/rbenv/rbenv) over RVM, If you don't already have it, the [`rbenv-installer`](https://github.com/rbenv/rbenv-installer) makes light work of it.

```bash
eval "$(rbenv init -)"
rbenv install 2.7.0
rbenv local 2.7.0
bundle
bundle exec jekyll serve --config ./_.config.yml
```
