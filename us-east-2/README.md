# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f562365700e3c5e8ce06b018074961d65133acdb
kustomize build ./user-configuration/production/us-east-2
```
