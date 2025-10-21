# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4811b99097e132a6daaf195fdd1212e62529624d
kustomize build ./user-configuration/development
```
