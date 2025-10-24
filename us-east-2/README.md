# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 059051b8f23d484534af8ab821cfafe5b1ad9d74
kustomize build ./user-configuration/production/us-east-2
```
