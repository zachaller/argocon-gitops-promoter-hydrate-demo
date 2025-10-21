# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 94ca7cabb9adc2b0a2cbcd6b4f9b130f79fd3930
kustomize build ./user-configuration/staging/e2e
```
