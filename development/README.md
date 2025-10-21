# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 851f237e43ec1c69b9babeaf7985f732a200f41e
kustomize build ./user-configuration/development
```
