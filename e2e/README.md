# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8f61a09a96289d337e8b3be37588d32bd50ea969
kustomize build ./user-configuration/staging/e2e
```
