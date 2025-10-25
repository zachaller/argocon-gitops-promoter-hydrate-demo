# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e5ec84a481aa3cea78bdcd3cb51ad34099431156
kustomize build ./user-configuration/production/us-west-1
```
