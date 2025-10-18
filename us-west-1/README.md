# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6ccc8ee95ccda34ad319f0af008ebf0d4615b6fc
kustomize build ./user-configuration/production/us-west-1
```
