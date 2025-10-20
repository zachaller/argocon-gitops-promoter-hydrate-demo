# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 88e481ae146fb45553abc990512fd4f84373f873
kustomize build ./user-configuration/development
```
