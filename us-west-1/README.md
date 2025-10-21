# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3de8f30054558ad40850506c6dac6a36f95c0034
kustomize build ./user-configuration/production/us-west-1
```
