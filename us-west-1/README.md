# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d7e46666c0a6641af45c87b421cb8f3ddfdeae5
kustomize build ./user-configuration/production/us-west-1
```
