# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 278ac9ec17f71e69b84dcb101ffc4269bf6186a8
kustomize build ./user-configuration/development
```
