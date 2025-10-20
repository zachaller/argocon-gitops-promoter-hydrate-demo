# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fcb71d25bd5521731bf300abf1b993fc5254a67a
kustomize build ./user-configuration/production/us-west-1
```
