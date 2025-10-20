# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fc348b72131174fcef35fbc4439375e697b9f615
kustomize build ./user-configuration/production/us-east-2
```
