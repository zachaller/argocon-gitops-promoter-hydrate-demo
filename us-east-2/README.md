# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e696f4c7338f0fde416e888123e6912f5af54a78
kustomize build ./user-configuration/production/us-east-2
```
