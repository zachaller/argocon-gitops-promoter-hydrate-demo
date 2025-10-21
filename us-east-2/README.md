# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b726a05f5ff318482aa23c0e29b21a393584a062
kustomize build ./user-configuration/production/us-east-2
```
