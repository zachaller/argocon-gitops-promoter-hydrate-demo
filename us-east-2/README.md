# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c3d612613be826bcbdb1a56f94635a24416f220f
kustomize build ./user-configuration/production/us-east-2
```
