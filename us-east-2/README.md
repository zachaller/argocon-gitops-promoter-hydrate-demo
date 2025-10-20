# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 570a55b41d9cda20b6aee06a7bf5503619b29c4e
kustomize build ./user-configuration/production/us-east-2
```
