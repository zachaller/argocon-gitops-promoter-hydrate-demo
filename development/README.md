# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e496e6ff45907dd4c16d579c6076c15240390837
kustomize build ./user-configuration/development
```
