# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f89e8e9cdcdb4402a97b536ed57078b63e519ef2
kustomize build ./user-configuration/production/us-east-2
```
