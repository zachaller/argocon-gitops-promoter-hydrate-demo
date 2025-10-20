# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3b0e1544b2b05aa5de16d43604ba9c0b2b2bc4ce
kustomize build ./user-configuration/staging/e2e
```
