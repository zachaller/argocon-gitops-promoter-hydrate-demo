# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1fd65e6e2ac9a733d0203625dcb21637f854953b
kustomize build ./user-configuration/development
```
