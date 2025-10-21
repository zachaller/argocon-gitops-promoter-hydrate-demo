# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 836d4245f6171bebd076dc9d43b373b06b6bcacc
kustomize build ./user-configuration/staging/e2e
```
