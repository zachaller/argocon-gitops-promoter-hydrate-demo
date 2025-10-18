# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5677278fbcfd765d6c1780b3e1215ef6c4178566
kustomize build ./user-configuration/staging/e2e
```
