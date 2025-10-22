# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d80f2816446e9fdb02d361bac223db646cc17d82
kustomize build ./user-configuration/production/us-east-2
```
