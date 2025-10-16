# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 31a7e6d56d4d9d5c97dc3d445cf5de39c114b076
kustomize build ./user-configuration/production/us-east-2
```
