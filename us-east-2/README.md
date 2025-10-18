# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ab728d7fe218a9615ab87f196a9825ab870923cc
kustomize build ./user-configuration/production/us-east-2
```
