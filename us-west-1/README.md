# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0fd1d545320665d896719980576aa0d5fef76cd6
kustomize build ./user-configuration/production/us-west-1
```
