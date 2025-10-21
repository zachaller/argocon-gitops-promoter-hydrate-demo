# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5ebb4a82bbf0615d17d1b0631e90127cdbed668f
kustomize build ./user-configuration/development
```
