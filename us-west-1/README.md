# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 56a9251e1307e20b76c8fcc6a1eec46b3c63137f
kustomize build ./user-configuration/production/us-west-1
```
