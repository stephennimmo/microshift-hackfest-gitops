# microshift-hackfest-gitops


Test Output
```
kustomize build app1/overlays/default
```

Apply to cluster
```
oc apply -k app1/overlays/default -n hackfest
```
