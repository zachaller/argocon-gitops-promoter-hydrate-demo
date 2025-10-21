# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 79c240f16f0f9a8af64d1c71ea41660cf30b9c0f
kustomize build ./user-configuration/production/us-east-2
```
