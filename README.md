<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-puppet-resource-api/brand/main/social/go-ruby-puppet-resource-api.png" alt="go-ruby-puppet-resource-api/go-ruby-puppet-resource-api.github.io" width="720"></p>

# go-ruby-puppet-resource-api.github.io

The organization's institutional landing page, served at
<https://go-ruby-puppet-resource-api.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-puppet-resource-api/docs](https://github.com/go-ruby-puppet-resource-api/docs), served at
<https://go-ruby-puppet-resource-api.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
