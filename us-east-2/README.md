# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 951f10c620df762d4c202608578e0b4e6e915655
kustomize build ./user-configuration/production/us-east-2
```
