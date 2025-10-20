# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 60d8bae30be2a9b81dfd312b10a9e8afe8938f4f
kustomize build ./user-configuration/production/us-west-1
```
