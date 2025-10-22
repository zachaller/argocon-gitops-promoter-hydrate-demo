# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a47cc760239ace181884859b1840728299ee987a
kustomize build ./user-configuration/production/us-east-2
```
