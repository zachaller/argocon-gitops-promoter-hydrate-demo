# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d69f6b95b1dfdd9652e6380f3ec39f4eb90448d8
kustomize build ./user-configuration/staging/integration
```
