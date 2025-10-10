# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 59083a19bcae2b88bdabab4215f8bc647b18b5bf
kustomize build ./user-configuration/development
```
