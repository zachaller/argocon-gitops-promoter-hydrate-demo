# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fa91bb921b72a0ce15235ba2deb16b5a5419e5ce
kustomize build ./user-configuration/development
```
