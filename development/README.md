# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2a4076a6d58fa256215a350b7758df1fcce20614
kustomize build ./user-configuration/development
```
