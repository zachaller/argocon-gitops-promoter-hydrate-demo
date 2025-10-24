# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 621e49b980e61785f495975826ac10640ebd9e85
kustomize build ./user-configuration/production/us-west-1
```
