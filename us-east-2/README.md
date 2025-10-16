# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 74c8ae3b26961bf192d1211aae3c92a6dd34b016
kustomize build ./user-configuration/production/us-east-2
```
