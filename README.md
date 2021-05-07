# ghostmirror-workflow
Join [@ghost_mirror](https://t.me/ghost_mirror)

You can use [this repos](https://github.com/ghostmirrorlab/mirror-bot-repos) as a template

First setup everything then push to your private Repository

Then Fork this Repo

Setup secrets in settings --> Secrets

```text
GH_TOKEN :- Your github personal access token, from https://github.com/settings/tokens
MIRROR_REPOSLUG :- Your Secret Repository, as in "<username>/<reponame>"
```

Then edit .github/workflows/*.yml

Change `GitHubMail`, `GitHubName` and `Branch` environment variable as your own

And That's it.

©ElytrA8
