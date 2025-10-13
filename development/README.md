# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cd3260e3618fc010c719262d45e00c6241025680
kustomize build ./user-configuration/development
```
