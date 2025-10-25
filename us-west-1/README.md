# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 48f95367849b1c9649d9b1e3373c10b0ad5f64e9
kustomize build ./user-configuration/production/us-west-1
```
