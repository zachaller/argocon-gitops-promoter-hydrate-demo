# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e3be3a1a381b8b05d73669cc95e67496f613a92b
kustomize build ./user-configuration/development
```
