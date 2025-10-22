# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout adc94b2d61963c6da737f672f734dcbf5e2d9a19
kustomize build ./user-configuration/development
```
