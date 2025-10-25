# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 37d567c0ed9b46fce118d772638075ecd2c724b2
kustomize build ./user-configuration/production/us-east-2
```
