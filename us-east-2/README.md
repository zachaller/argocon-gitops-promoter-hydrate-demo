# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2fad7fa0ec1ed58db5858be42a6e87b071614ff2
kustomize build ./user-configuration/production/us-east-2
```
