# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a0d320820a7bcd3fd97987f7e8fb03d210c17f0b
kustomize build ./user-configuration/production/us-east-2
```
