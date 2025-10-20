# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 304aedb919345ea96c60393de2317a0a6ddfd354
kustomize build ./user-configuration/staging/e2e
```
