# Ghost content

This folder is mounted as Ghost's content directory when GitHub Actions publishes the site.

Copy these paths from your local blog (`~/.ghost/content`) before you want your real posts online:

```
content/data/          # SQLite database (ghost.db)
content/images/
content/themes/
```

Leave `.env` and payment or email secrets out of git.

If this folder only contains this README, the workflow can still start Ghost and publish the default welcome page. Replace these files with your snapshot, then push again, when the posts should be the ones you wrote.

Setup guides:

- [Getting Started](https://github.com/paladini/ghost-on-github-pages/blob/master/docs/v3/GETTING-STARTED.md)
- [Docker Compose](https://github.com/paladini/ghost-on-github-pages/blob/master/docs/v3/DOCKER.md)
- [CI / Pages](https://github.com/paladini/ghost-on-github-pages/blob/master/docs/v3/CI.md)
