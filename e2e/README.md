# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 32bef0f0c31c9c09520484da8f239adc0247a3c7
kustomize build ./user-configuration/staging/e2e
```
