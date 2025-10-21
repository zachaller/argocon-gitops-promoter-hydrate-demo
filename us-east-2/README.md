# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 51e5e3ee03aa3996f8a70812f129a5c6c81f6afc
kustomize build ./user-configuration/production/us-east-2
```
