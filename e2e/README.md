# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c85c4409e32cf8681e5500901a9f7c371c3f1695
kustomize build ./user-configuration/staging/e2e
```
