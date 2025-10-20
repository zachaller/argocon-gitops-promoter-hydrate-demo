# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ef3f75cc585aed5417e9d112fc0a5a77f391acae
kustomize build ./user-configuration/production/us-west-1
```
