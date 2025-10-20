# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e0b33ac3e2e1c7d7b86ffe56694467cc5aa060f1
kustomize build ./user-configuration/development
```
