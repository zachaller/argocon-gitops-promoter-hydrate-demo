# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7a37d59cf692eb6bcac05890758fb921c92c5ff0
kustomize build ./user-configuration/development
```
