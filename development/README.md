# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3fea38b83d84c95af25e42d33853326aa05c6d7a
kustomize build ./user-configuration/development
```
