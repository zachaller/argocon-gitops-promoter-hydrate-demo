# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2c180cbc90afbf698fa03b178e6d80bdad40b415
kustomize build ./user-configuration/production/us-west-1
```
