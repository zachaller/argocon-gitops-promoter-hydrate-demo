# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6a29087627acb5e10558daa5d6479309f76198c1
kustomize build ./user-configuration/production/us-east-2
```
