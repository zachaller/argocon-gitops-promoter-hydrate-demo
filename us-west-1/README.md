# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 803a83b73ac6618d576ba82d96532bf640ee7f87
kustomize build ./user-configuration/production/us-west-1
```
