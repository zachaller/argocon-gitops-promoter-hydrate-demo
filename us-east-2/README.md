# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a8de994bd088f0699d20bc216629e699f61ed007
kustomize build ./user-configuration/production/us-east-2
```
