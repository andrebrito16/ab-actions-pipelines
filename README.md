# Github Actions Pipelines

This is a project inspired on Filipe Forattini [ff-iac-github-actions](https://github.com/filipeforattini/ff-iac-github-actions). All credits to Filipe for do the original work. I just have made some changes.

### Repository Secrets

You have to setup some repository secrets to pipeline works

| Name | Description |
| ---: | --- |
| GPG_PASSPHRASE |  |
| KUBE_CONFIG | Your `~/.kube/config` file as base64. |
| PIPELINE_DEPLOY_TOKEN | A GitHub token, see the permissions below. |
| REGISTRY_USERNAME | Registry username. |
| REGISTRY_PASSWORD | Registry password. |