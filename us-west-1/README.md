# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c1ba10ad85cd470ea808c3436381b32547563f6e
kustomize build ./user-configuration/production/us-west-1
```
