---
title: "Look and Feel"
weight: 1
---

Edit the `config.toml` to match the following content:

```toml
baseURL = "/"
languageCode = "en-us"
theme = "learn"

[outputs]
home = [ "HTML", "RSS", "JSON"]

[params]
showVisitedLinks = true
disableBreadcrumb = false
disableNextPrev = false
themeVariant = "red"
```

This will enable cool features such as the search engine, the navigation, the
breadcrumb and the checkmarks next in the table of content for visited links.

And, the left sidebar is now red!

Customize the logo and favicon with cool branding:

```sh
mkdir -p static/images/
curl https://upload.wikimedia.org/wikipedia/fr/c/cb/Red_hat_logo.png -o static/images/logo.png
mkdir -p layouts/partials
echo '<img src="/images/logo.png" />' > layouts/partials/logo.html
curl "http://www.myiconfinder.com/icon/download/16895e53b6d340dffee1c9b84d90ca94-Redhat.png~10057" -o static/images/favicon.png
```