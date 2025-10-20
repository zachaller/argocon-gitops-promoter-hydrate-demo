# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 89da0724cfdd0eef0ad7271acf6a5a3c1362db17
kustomize build ./user-configuration/development
```
