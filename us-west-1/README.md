# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b716238c1f6772965859b7c7f17273e72aa32c0
kustomize build ./user-configuration/production/us-west-1
```
