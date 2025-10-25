# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8765bc1dda8994a585e266155ae83f59066f392a
kustomize build ./user-configuration/production/us-east-2
```
