# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ca4e66b4a38edfa5d3c19478cf42dc8ab2e4c083
kustomize build ./user-configuration/production/us-east-2
```
