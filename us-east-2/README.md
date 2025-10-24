# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c2e351aba967f8b2411d6a7b69520f973911e9bf
kustomize build ./user-configuration/production/us-east-2
```
