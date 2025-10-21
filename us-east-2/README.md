# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ef665093aaa49f7327d691af567c4f9c6a86322f
kustomize build ./user-configuration/production/us-east-2
```
