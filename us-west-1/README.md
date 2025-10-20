# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e137b2e2e29670445c3a14948bd1789fbc49a89a
kustomize build ./user-configuration/production/us-west-1
```
