# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2deeeaed4a922e67c1a50838e01c6694037a88b8
kustomize build ./user-configuration/staging/e2e
```
