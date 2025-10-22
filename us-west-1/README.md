# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 068d973562a8dc749a89fd0dc1b403d35cc30c4d
kustomize build ./user-configuration/production/us-west-1
```
