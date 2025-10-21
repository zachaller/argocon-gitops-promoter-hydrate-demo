# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 26d682576845a1a179448b08db0a5404fe796a61
kustomize build ./user-configuration/staging/integration
```
