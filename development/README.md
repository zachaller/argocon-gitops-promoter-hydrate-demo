# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f4f5f8adb79a9e698527a550f1b7dcf513613d36
kustomize build ./user-configuration/development
```
