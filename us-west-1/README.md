# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1de2fe3d152f067582793757f6e5781a869ca85a
kustomize build ./user-configuration/production/us-west-1
```
