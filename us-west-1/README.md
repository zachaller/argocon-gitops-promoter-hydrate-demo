# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ce2072f5c04f157d9c7dc8e15e540e8ee939422a
kustomize build ./user-configuration/production/us-west-1
```
