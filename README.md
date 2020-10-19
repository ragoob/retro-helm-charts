# retro-helm-charts
Kubernetes charts for retro app

https://github.com/emad-elsaid/retro

# Installation

    helm install retro-app -n your-name-space-name .
    
#### you can override values.yaml values:

    helm install retor-app -n your-name-space-name --set values.yaml-key=your-value
#### example :
 

    helm install retro-app -n default --set containerPort=5000 --set ingress.enabled=true .



 
 
 
 
