# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 95fc8e56770c4b983d09a89317a4375b0f948fc3
kustomize build ./user-configuration/production/us-west-1
```
