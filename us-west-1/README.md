# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c40fb0345015dc81c45a7293d0d2f877e2f8c13b
kustomize build ./user-configuration/production/us-west-1
```
