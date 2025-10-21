# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5ab1f1fae945e608c17420459d288efc02f69de7
kustomize build ./user-configuration/staging/e2e
```
