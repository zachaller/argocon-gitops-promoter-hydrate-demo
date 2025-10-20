# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0ebd134130eaabddf308c9be662a47dee6483859
kustomize build ./user-configuration/production/us-east-2
```
