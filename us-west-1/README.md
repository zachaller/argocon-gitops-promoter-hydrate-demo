# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 95b1596ef065618c669a9a54a13d6434b4c46878
kustomize build ./user-configuration/production/us-west-1
```
