# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 472575602feee527a9e80c0336e9876daa5a57fc
kustomize build ./user-configuration/staging/integration
```
