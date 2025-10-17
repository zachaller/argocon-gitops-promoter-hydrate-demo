# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4d7065a2e37057f912e26d5f0967d6adb75f2ba0
kustomize build ./user-configuration/staging/integration
```
