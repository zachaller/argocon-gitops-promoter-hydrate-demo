# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 538018a122c05f6cf9796a3a1a8781967b3e65f3
kustomize build ./user-configuration/production/us-east-2
```
