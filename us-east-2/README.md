# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0e339990cf75dd980ffa1462f63f4c62372fc452
kustomize build ./user-configuration/production/us-east-2
```
