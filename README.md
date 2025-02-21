# Using the code / YAML files

- There are two hands-on chapters in this book, Chapter 03 and Chapter 09.
- The `CH03` folder is the starting point for Chapter 03 exercises and has the application code that will be packaged into a Docker container.
- The `CH09` folder is the starting point for Chapter 09 and is deliberately empty.
- The `solution` folder is where you can find the completed YAML files (to copy from if you do not wish to create them from scratch).

## Chapter 03 exercise to file mapping

Exercise | File
-------- | ----
Creating a Dockerfile | [Dockerfile](solution/CH03/Dockerfile)

## Chapter 09 exercise to YAML file mapping

Exercise | YAML file
-------- | ---------
Creating your first pod | [pod.yaml](solution/CH09/pod.yaml)
Deployments | [deployment.yaml](solution/CH09/deployment.yaml)
Services | [services.yaml](solution/CH09/service.yaml)
Creating a Persistent Volume (minikube) | [pv-minikube.yaml](solution/CH09/pv-minikube.yaml)
Creating a Persistent Volume (Play with Kubernetes) | [pv-play-with-kubernetes.yaml](solution/CH09/pv-play-with-kubernetes.yaml)
Creating a Persistent Volume Claim | [pvc.yaml](solution/CH09/pvc.yaml)
Updating the deployment to use the volume | [deployment-with-volume.yaml](solution/CH09/deployment-with-volume.yaml)
StatefulSets | [statefulset.yaml](solution/CH09/statefulset.yaml)
DaemonSets | [daemonset.yaml](solution/CH09/daemonset.yaml)