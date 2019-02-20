---
title: "Theme"
weight: 3
---

The [learn theme](https://learn.netlify.com/en/) for Hugo is one of the most
suited design for training instructions. It features breadcrumb, navigation
buttons, table of content in the sidebar, checkmark to know which sections
the participant visited and much more!

Install the learn theme:

```sh
cd hugo-workshop
git init
git submodule add https://github.com/matcornic/hugo-theme-learn.git themes/learn
echo 'theme = "learn"' >> config.toml
```