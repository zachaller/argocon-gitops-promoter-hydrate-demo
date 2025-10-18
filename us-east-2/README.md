# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 69bd87360fe3e7a457ad47738d8c5fc032b88a2e
kustomize build ./user-configuration/production/us-east-2
```
