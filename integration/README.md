# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7251891eb1c73606b8cb5809aee76fd2c3cce313
kustomize build ./user-configuration/staging/integration
```
