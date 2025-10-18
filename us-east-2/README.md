# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4dcdfb4ecf86ff7bd471eebe06dbf2128de79f80
kustomize build ./user-configuration/production/us-east-2
```
