# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a886951958cc89542771e156ea0135bb6a4a7ac7
kustomize build ./user-configuration/staging/e2e
```
