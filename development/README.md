# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c75c0fe7243b997febb4e231bce54ed6e1461206
kustomize build ./user-configuration/development
```
