# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 124148a5ca221bce8f8f3184f584aa3f357b5a79
kustomize build ./user-configuration/production/us-east-2
```
