# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1200bf33200f5f0bd7f465e2e7434a7ac9654266
kustomize build ./user-configuration/production/us-east-2
```
