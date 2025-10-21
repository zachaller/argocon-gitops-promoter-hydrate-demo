# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1b2d27d1504754da403bf1e8d819858ff526acfa
kustomize build ./user-configuration/staging/integration
```
