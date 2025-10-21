# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ed33f0133352e32d0e825935064094ffee59f3ba
kustomize build ./user-configuration/production/us-west-1
```
