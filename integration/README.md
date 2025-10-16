# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 42eab409c3b6233cec215bc3f2a9e2d8e7e15ae3
kustomize build ./user-configuration/staging/integration
```
