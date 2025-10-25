# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a10bd5ef874f380398d73ed005d00d5d4cec74af
kustomize build ./user-configuration/production/us-west-1
```
