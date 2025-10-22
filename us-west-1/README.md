# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 73e23edb004c2fb7715b55e21870f465e8472ae4
kustomize build ./user-configuration/production/us-west-1
```
