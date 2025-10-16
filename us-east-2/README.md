# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3f5ba93f5c6ac651224fda8524cca0a85ffc2ac3
kustomize build ./user-configuration/production/us-east-2
```
