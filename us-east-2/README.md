# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6404bc31719bfc74630ff516948063abbf6c9da6
kustomize build ./user-configuration/production/us-east-2
```
