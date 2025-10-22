# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 09864f3b9b0df7b6eb36465ae4adec7868762430
kustomize build ./user-configuration/production/us-east-2
```
