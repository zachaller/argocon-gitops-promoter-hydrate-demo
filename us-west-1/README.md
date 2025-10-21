# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 36ed1204d06322ec838922094bab197bdcddc93b
kustomize build ./user-configuration/production/us-west-1
```
