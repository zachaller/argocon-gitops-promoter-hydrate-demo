# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 915b215afd4bebf9bfa61eb3a5560c77a0cfc78e
kustomize build ./user-configuration/development
```
