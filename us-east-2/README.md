# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 08d65bedb4c2165d807663244481ae462ce95ba5
kustomize build ./user-configuration/production/us-east-2
```
