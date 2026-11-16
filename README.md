# Ghost on GitHub Pages starter

Write in Ghost. This repository publishes the static blog on GitHub Pages.

It is a template. The toolkit lives in [paladini/ghost-on-github-pages](https://github.com/paladini/ghost-on-github-pages). A live example is the [v3 demo](https://paladini.github.io/ghost-on-github-pages-demo/).

## Use this template

1. Click **Use this template** and create your repository.
2. Open **Settings → Pages** and set **Source** to **GitHub Actions**.
3. Put your Ghost content in [`content/`](content/README.md). Until you do, the first run can publish a fresh Ghost welcome page.
4. Push to `main` or `master`.

The workflow uses your GitHub username and repository name. For a project site the public URL is `https://USER.github.io/REPO`.

If the repository is named `USER.github.io` (a user site), edit [`.github/workflows/publish-static.yml`](.github/workflows/publish-static.yml):

- `production_domain`: `https://USER.github.io`
- `gh_repo`: `USER.github.io`

## Write the posts

Follow [Getting Started](https://github.com/paladini/ghost-on-github-pages/blob/master/docs/v3/GETTING-STARTED.md) or the [Docker Compose guide](https://github.com/paladini/ghost-on-github-pages/blob/master/docs/v3/DOCKER.md) in the toolkit repository. Ghost runs on your computer. GitHub Pages only receives the static files.

Do not commit secrets, SMTP keys, or member payment settings.

## License

[MIT](LICENSE)
