# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d043c69068f4eada622e28eab3f2902d9a73734f
kustomize build ./user-configuration/development
```
