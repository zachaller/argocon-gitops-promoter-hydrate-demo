# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4e0306f2a08e08f266f1281a546234ad868f25e9
kustomize build ./user-configuration/development
```
