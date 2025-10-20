# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout baf9023a9b2448f11f544160bbe4ffd0d7982177
kustomize build ./user-configuration/staging/integration
```
