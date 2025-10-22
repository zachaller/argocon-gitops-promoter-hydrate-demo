# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f798eca2eaf44c3d9679ae3c05b546e9770dfe2b
kustomize build ./user-configuration/development
```
