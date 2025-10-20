# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5ea5bd7f2cda76b4a99f37420b6863986b5366c1
kustomize build ./user-configuration/production/us-west-1
```
