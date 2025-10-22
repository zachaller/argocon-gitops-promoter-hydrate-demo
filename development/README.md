# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9b497bd2c1ca61465e4417b956e11140bb51b3de
kustomize build ./user-configuration/development
```
