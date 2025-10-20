# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5c76db6c2e692b97aa57c03dc896ac3c4e08b623
kustomize build ./user-configuration/production/us-east-2
```
