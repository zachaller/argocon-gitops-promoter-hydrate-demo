# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6978a5392cc2a01b93b813df8586511f1faebf67
kustomize build ./user-configuration/production/us-west-1
```
