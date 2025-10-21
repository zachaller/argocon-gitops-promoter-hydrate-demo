# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 77ef41244f6c1848f4b5e0cdfa09aa3d9204c774
kustomize build ./user-configuration/staging/e2e
```
