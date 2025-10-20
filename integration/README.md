# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6ba733564a1b7744da6b4762575d865e170c848a
kustomize build ./user-configuration/staging/integration
```
