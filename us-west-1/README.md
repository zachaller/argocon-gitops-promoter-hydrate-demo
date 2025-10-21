# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2a1942ac2fe321f6592a405e012c54c0bcf3a7b3
kustomize build ./user-configuration/production/us-west-1
```
