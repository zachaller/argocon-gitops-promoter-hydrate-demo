# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 52a7e3e8069c4aa2dcc90999ec5acd305e86bcc2
kustomize build ./user-configuration/production/us-west-1
```
