# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a107d6083a1de9689f80b1070974102b7794b3b6
kustomize build ./user-configuration/production/us-west-1
```
