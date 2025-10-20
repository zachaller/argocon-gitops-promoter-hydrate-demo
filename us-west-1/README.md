# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c68c41b2a1f2fd57203ecf4064bc64b5fb9a06db
kustomize build ./user-configuration/production/us-west-1
```
