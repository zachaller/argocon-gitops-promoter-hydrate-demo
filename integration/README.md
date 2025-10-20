# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 51633c013cec9b9ba93b6f4a87e010fd358e4d57
kustomize build ./user-configuration/staging/integration
```
