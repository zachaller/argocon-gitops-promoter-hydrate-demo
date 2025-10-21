# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b0f1d155ff7eed294ddcbacdfb7b5ed15733f5d9
kustomize build ./user-configuration/staging/e2e
```
