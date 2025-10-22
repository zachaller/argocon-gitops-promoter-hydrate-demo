# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c702b004e00f44b05f6d1131b289b7bd162242dc
kustomize build ./user-configuration/production/us-west-1
```
