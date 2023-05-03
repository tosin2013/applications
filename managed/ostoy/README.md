# OSToy
## v1.5.0

A simple Node.js application that deploys to OpenShift. It is used to help
explore the functionality of Kubernetes. This toy application has a user interface
which you can:

* write messages to the log (stdout / stderr)
* intentionally crash the application to view auto repair
* toggle a liveness probe and monitor OpenShift behavior
* if provided; read config maps, secrets, and env variables
* if connected to shared storage, read and write files
* check network connectivity, intra-cluster DNS, and intra-communication with an
  included microservice
* increase the load to test out Horizontal Pod Autoscaler
* if deployed to AWS, use the app to read the contents of an S3 bucket created with the AWS Controller for Kubernetes

Git URL: https://github.com/tosin2013/ostoy

![20230424120817](https://i.imgur.com/OSUFdlN.png)

