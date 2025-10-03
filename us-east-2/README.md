# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c931e87cdc291a10d048e53d4f09747ec632f377
kustomize build ./user-configuration/production/us-east-2
```
