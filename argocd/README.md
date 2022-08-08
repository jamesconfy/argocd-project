# ArgoCD Manifests

Place the ArgoCD manifests in this directory.

This get the deployment from [Kubernetes](https://github.com/jamesconfy/kubernetes/tree/main/python-manifests), and use it to create an application in argocd.
To do this, just run `kubectl apply -f argocd-python.yml`

Note: You need to have a namespace called argocd first and also default namespace
