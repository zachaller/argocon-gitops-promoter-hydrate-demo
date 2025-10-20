# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f657e0e1a90baf6dedfc5e37403737f312942aa7
kustomize build ./user-configuration/staging/integration
```
