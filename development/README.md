# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 695930890dd88e4ba38ec5abcfeafe93a446f1ec
kustomize build ./user-configuration/development
```
