# How to use this?

This is a simple html page served through nginx using html.

This app has been built using Roost Desktop. Check it out at roost.io.

It is super easy to deploy it using Roost.
1. Open the project in Roost.
2. Right click on the Dockerfile and select the option to build it.
3. Right click on the helloworld-pod.yaml and select the option to apply it to ZKE cluster.

Done ...

You may now access this webpage and using url http://roost-worker:30909 in your browser.

Share the microservice with your friends and use Roost's collaboration features to develop more microservices with them.

You can also enter the following in your RKT Console if you like using cli -
- Build it the docker file.
```bash
docker build -t helloworld-html .
```
- Deploy it using the given yaml
```bash
kubectl create -f helloworld-pod.yaml
```