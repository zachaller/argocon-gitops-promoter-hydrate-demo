# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bf1a36f23eb02280944a4011c1067ea3980feb65
kustomize build ./user-configuration/production/us-west-1
```
