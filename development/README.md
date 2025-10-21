# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a2796b9db597f71977412b1f4eba70e3d8504fc7
kustomize build ./user-configuration/development
```
