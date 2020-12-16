# github-actions-example

Example repo for using Gimlet CLI with Github Actions

Check the Gimlet manifest file in `.gimlet/` and the Github Actions code under `.github/workflows`.

## Builds

https://github.com/gimlet-io/github-actions-example/actions

## GitOps repo

https://github.com/gimlet-io/github-actions-example-gitops

## Forking this repo

If you fork the repo, you must add a Secret called `PAT` in the repo settings.

Create a Personal Access Token in your settings and add the `repo` scope for the GitOps repo writing, and the `write:packages` scope for Github Container Registry push access.

NOTE: At the time of creation Github Container Registry is in public beta. Follow this guide to enable it for your account or organization
