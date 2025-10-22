# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ce07d1a9274000a0be5b1499e579a5a1112d068e
kustomize build ./user-configuration/production/us-east-2
```
