# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9c3b30041c31a81d106b39b08bfe9f70f116a877
kustomize build ./user-configuration/staging/integration
```
