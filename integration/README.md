# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e5fcfb704eaca32ed50fd0a9f9b43b08436843a7
kustomize build ./user-configuration/staging/integration
```
