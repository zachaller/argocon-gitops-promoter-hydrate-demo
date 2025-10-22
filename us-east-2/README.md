# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout eb79fd7766bdfb45f987e3d71fabf640dd9f9520
kustomize build ./user-configuration/production/us-east-2
```
