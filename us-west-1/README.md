# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout da5078048a99b0663fc1f785ea4fd802686115e1
kustomize build ./user-configuration/production/us-west-1
```
