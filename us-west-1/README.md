# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c4ab90883fdc5e89942370a90d5eff1fdad0f9cd
kustomize build ./user-configuration/production/us-west-1
```
