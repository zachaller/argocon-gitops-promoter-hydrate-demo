# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 354f06f0c6016f7b96e2bf86c60a49665ba51e7d
kustomize build ./user-configuration/production/us-east-2
```
