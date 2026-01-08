# To install superset (For expermental purposes only, prod requires lot more work and security hardening etc)

* Get a working Kubernetes cluster
* Create namespace "superset"
* In below list, some commands are completely optional and for informational purpose only! :)

```  
# which helm
# which kubectl
# kubectl get namespace
# kubectl create namespace superset
# helm repo list
# helm repo add superset https://apache.github.io/superset
# helm update
# helm search repo superset
# helm upgrade --install superset superset/superset -n superset -f values.yaml
```
