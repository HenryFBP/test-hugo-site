# test-hugo-site
test hugo site. see https://gohugo.io/hosting-and-deployment/hosting-on-github/

Make sure that your repo is named `<username>.github.io`.

Also make sure your branch name is correct in `gh-pages.yml`:

```yml
on:
  push:
    branches:
      - master  # Set a branch to deploy
```