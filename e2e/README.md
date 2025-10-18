# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 139e78ed53c28b964ad2b193cb38a53bc656987c
kustomize build ./user-configuration/staging/e2e
```
