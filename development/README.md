# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b1a825b460d8cf5326fef04eca06f89eb723bd87
kustomize build ./user-configuration/development
```
