# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1cc6cf579440dce01ddc68e281bc155387360f4a
kustomize build ./user-configuration/staging/e2e
```
