# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2236baf6ed7c14a96b71c481973b3a9071166f49
kustomize build ./user-configuration/staging/e2e
```
