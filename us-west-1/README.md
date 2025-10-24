# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1df6bb185170c2283b876d1ba61bdf61871c12a2
kustomize build ./user-configuration/production/us-west-1
```
