# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2c59d53a9b3bca14fdc831ade9d5fa6760ba50de
kustomize build ./user-configuration/production/us-east-2
```
