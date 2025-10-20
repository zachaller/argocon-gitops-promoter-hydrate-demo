# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 42405edf600bd188e64c379f02277466ad179869
kustomize build ./user-configuration/production/us-west-1
```
