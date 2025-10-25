# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f9d5561af34a380b2e5d3362796cbe166a32c59d
kustomize build ./user-configuration/production/us-west-1
```
