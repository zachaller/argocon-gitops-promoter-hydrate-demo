# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5de317155a82fb8b3e63561b4def10a1ca743733
kustomize build ./user-configuration/development
```
