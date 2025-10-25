# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d712d9e2db8790a3a1753c2301475b9061345489
kustomize build ./user-configuration/development
```
