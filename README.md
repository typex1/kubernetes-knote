This is a simple kubernetes-based microservices application consisting of a JavaScript frontend and a MongoDB backend. This was originally developed by https://github.com/learnk8s/knote-js and can be used in the context of an Amazon EKS deployment example.

We can deploy this application in working Kubernetes cluster (be it a native Kubernetes one or an Amazon EKS) using kubectl commands and the available YAML configuration files.

Frontend deployment:

kubectl apply -f knote.yaml

Backend deployment:

kubectl apply -f mongo.yaml
