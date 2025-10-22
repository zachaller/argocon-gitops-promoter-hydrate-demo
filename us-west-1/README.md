# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 34cd85463f2a3fd5e0959c213a1c0476d49f6b7e
kustomize build ./user-configuration/production/us-west-1
```
