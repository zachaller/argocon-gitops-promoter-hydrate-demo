# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3a789c36251f697204de7d853cb11c56088f1c4b
kustomize build ./user-configuration/staging/e2e
```
