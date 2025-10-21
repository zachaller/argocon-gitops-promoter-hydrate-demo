# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a0075418f6e8256d82c28f48f056a03a95fa0478
kustomize build ./user-configuration/production/us-west-1
```
