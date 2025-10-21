# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 53adda975e9b51afa306251c1a2b215a506a440e
kustomize build ./user-configuration/production/us-west-1
```
