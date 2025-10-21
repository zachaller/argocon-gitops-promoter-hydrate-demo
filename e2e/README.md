# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 947a49caf4262dbed7b0cd30566d3cfaa8c9c7a4
kustomize build ./user-configuration/staging/e2e
```
