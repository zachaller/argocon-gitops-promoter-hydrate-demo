# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aa40623c078d64ef5dfabbf3d915aabb8a436acd
kustomize build ./user-configuration/development
```
