# Manifests with prompts
| NAME                                        | PROMPT                                                    | DESCRIPTION                                                         | EXAMPLE                                                                              |
|---------------------------------------------|-----------------------------------------------------------|---------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| app.yaml                                    | create deploy app.yaml use image is gcr.io/k8s-k3s/demo:v.1.0.0                  | Deployment App                                                                 |  [app.yaml](yaml/app.yaml)                                  |
| app-livenessProbe.yaml                      | create deploy app-livenessProbe                                                         | Liveness Probe                                                                  | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)                                                                                   | 
| app-readinessProbe.yaml                     |create deploy app-readinessProbe.                                                       | Readiness Probe	                                                                  |  [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml)                                                                                    |
| app-volumeMounts.yaml                       | create deploy app-volumeMounts                                                        | Volume Mounts                                                                  |  [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)                                                                                    | 
| app-cronjob.yaml                            | create deploy app-cronjob.yaml with on failure restart policy                               | Cron Job                                                                  |   [app-cronjob.yaml](yaml/app-cronjob.yaml)                                                                                      | 
| app-job.yaml                                |  create deploy app-job.yaml that launches cleanup process on the pod                        | App Job                                                                  |[app-job.yaml](yaml/app-job.yaml)                                                                                     | 
| app-multicontainer.yaml                     | create deploy app-multicontainer.yaml where the main image is gcr.io/k8s-k3s/demo:v.1.0.0"   | App Multicontainers                                                                    |[app-multicontainer.yaml](yaml/app-multicontainer.yaml)       
| app-secret-env.yaml                         | create deploy app-resources.yaml, requirements are 256mb memory and limits are 1024mb"        | App with secret                                                                    | [app-resources.yaml](yaml/app-resources.yaml)
| app-resources.yaml                          | create deploy app-secret-env.yaml which accepts encrypted base64                     | Resources                                                                   |[app-secret-env.yaml](yaml/app-secret-env.yaml) |   
