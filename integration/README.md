# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 385a4bcf53b74cc94e02d68367a14edcdbd9f2ce
kustomize build ./user-configuration/staging/integration
```
