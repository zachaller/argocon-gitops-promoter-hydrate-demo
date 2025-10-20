# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c09bd53ac2eb2fb92a4812c18aa7eb3d710e5a6
kustomize build ./user-configuration/staging/e2e
```
