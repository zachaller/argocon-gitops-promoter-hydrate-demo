# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3be31e3714c36756d2fc60a988aba1a023f71ed6
kustomize build ./user-configuration/development
```
