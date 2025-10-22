# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3207ab8d7320dcb59fbf298c04810eee0b65d9fb
kustomize build ./user-configuration/staging/e2e
```
