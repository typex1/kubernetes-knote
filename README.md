This is a simple kubernetes-based microservices application that will help you to upload an Image with Notes. It is designed as a 2 tier architecture (frontend - nodejs and backend - mongodb). This was originally developed by https://github.com/learnk8s/knote-js and modified it for the educational demo purpose only.

We can deploy this application in working kubernetes cluster using kubectl commands or using YAML configuration files.

Frontend:

kubectl apply -f knote.yaml

Backend:

kubectl apply -f mongo.yaml

Recommended Documents for references:
-------------------------------------


