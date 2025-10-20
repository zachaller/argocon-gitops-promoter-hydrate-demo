# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bab4ca89aee294caa3632672e853f64028ad6652
kustomize build ./user-configuration/production/us-east-2
```
