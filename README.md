# Simple Microservice / kubernetes demo
This example will help any get used to with kubernetes and can also serve as a very simple example of how micro services works. We have two service running here, webserver and mysql server communication to each other to make the application running. 

#### Note:
I prepare this docs to teach my co-workers how k8s works. It might help you too. 

## How to use it:

- 1. Build the image inside custom-image directory and push it to container registry or to your local machine if you are trying it locally no need to push to registry.
- 2. Change the image name in the app.yaml
- 3. Deploy the k8s manifests
