# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 23be5728b0712a6cff5c3c0b56673da29ab39401
kustomize build ./user-configuration/production/us-east-2
```
