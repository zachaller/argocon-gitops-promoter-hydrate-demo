# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a4f08690a92a4e97654bf6e094d260f3c7ca6303
kustomize build ./user-configuration/production/us-west-1
```
