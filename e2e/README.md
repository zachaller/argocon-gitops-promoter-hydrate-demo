# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 15f47920452b8da0cb3ab9470a926a5f3b543d88
kustomize build ./user-configuration/staging/e2e
```
