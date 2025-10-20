# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 17c7c763082ee262a0a6bb2b7856bf4032ba9ce3
kustomize build ./user-configuration/production/us-west-1
```
