# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fff5111512fe25f93b02b20fb2ee68cec2bfcca6
kustomize build ./user-configuration/production/us-west-1
```
