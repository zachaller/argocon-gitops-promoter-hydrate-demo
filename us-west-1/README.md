# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0d852ed26043cb2a481197ed45f504bf78bb1720
kustomize build ./user-configuration/production/us-west-1
```
