# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bd6bc820db075978fc29ec50003a2f9c9c4cf071
kustomize build ./user-configuration/production/us-east-2
```
