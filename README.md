# demo
| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| app.yaml | kubectl apply -f app.yaml | An app.yaml file in Kubernetes is a configuration file that defines the deployment of an application within a Kubernetes cluster. | [app.yaml](/yaml/app.yaml) |
| app-livenessProbe.yaml | kubectl apply -f app-livenessProbe.yaml |  Liveness prob is a diagnostic tool used to determine the health of a container within a Pod. It is defined in the Pod's configuration and periodically checks whether the container is functioning properly. | [app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | kubectl apply -f app-readinessProbe.yaml | ReadinessProbe is a configuration option that helps ensure that a container is ready to accept traffic before it starts receiving requests. | [app-readinessProbe.yaml](/yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | kubectl apply -f app-volumeMounts.yaml | VolumeMounts is a configuration option that allows you to mount volumes into containers within a Pod. This configuration is essential for managing data persistence, sharing files between containers, and providing configuration data to applications. | [app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | kubectl apply -f app-cronjob.yaml | Cronjob is meant for performing regular scheduled actions such as backups, report generation, and so on. | [app-cronjob.yaml](/yaml/app-cronjob.yaml) |
| app-job.yaml | kubectl apply -f app-job.yaml | Job creates one or more Pods and will continue to retry execution of the Pods until a specified number of them successfully terminate. As pods successfully complete, the Job tracks the successful completions. | [app-job.yaml](/yaml/app-job.yaml) |
| app-multicontainer.yaml | kubectl apply -f app-multicontainer.yaml | Multi-container is a configuration that allows you to run more than one container within the same Pod. These containers share the same network namespace and can communicate with each other using localhost. | [app-multicontainer.yam](/yaml/app-multicontainer.yaml) |
| app-resources.yaml | kubectl apply -f app-resources.yaml | Resources configuration within a Pod or Deployment specification allows you to define the compute resource requirements and constraints for the containers running within the Pod. | [app-resources.yaml](/yaml/app-resources.yaml) |
