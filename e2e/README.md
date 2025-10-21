# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 936c89420ee60e19661173e2e15dde7a2b9577a2
kustomize build ./user-configuration/staging/e2e
```
