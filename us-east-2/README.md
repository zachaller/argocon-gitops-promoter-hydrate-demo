# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2e386b34599c012452fa0aaae2f409e731a6328b
kustomize build ./user-configuration/production/us-east-2
```
