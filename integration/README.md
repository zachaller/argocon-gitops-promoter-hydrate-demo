# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 632fcc71c1f160725ffae882d74b5dbca542bb8c
kustomize build ./user-configuration/staging/integration
```
