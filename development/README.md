# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 71a1b9652646498e5fdc6baad7d428873e79ac94
kustomize build ./user-configuration/development
```
