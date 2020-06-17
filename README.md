# GitHub Page

## Build

```bash
bundle install
```

```bash
bundle exec jekyll serve
```

GitHub page has dependency on

```yaml
gem "jekyll", "~> 3.7.3"
```

Deployment requires a re-build every time I push to master. The build process converts template HTML
to HTMl with real values.
