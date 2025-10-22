# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3624bcc19efde37c5ee8716bbbb787349116d443
kustomize build ./user-configuration/development
```
