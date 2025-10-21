# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4483813eefa9f1ccb96bc9dc453d0263feb35b42
kustomize build ./user-configuration/production/us-east-2
```
