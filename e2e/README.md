# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b305c000e335999d04adc2b41453e331d0b18e19
kustomize build ./user-configuration/staging/e2e
```
