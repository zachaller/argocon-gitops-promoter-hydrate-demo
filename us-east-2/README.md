# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0b6b078127ad583666fa693f9775292a70d4b325
kustomize build ./user-configuration/production/us-east-2
```
