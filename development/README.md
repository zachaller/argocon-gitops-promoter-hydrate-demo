# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 40557e68a0fd58fb43c9ee9a3427346165ec1f60
kustomize build ./user-configuration/development
```
