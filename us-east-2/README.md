# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1f34c093e6a343de893539e62c6a52a2c9419367
kustomize build ./user-configuration/production/us-east-2
```
