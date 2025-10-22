# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 209404f7b491fe2b8ce1aef57c016f95d0b2e8bf
kustomize build ./user-configuration/staging/e2e
```
