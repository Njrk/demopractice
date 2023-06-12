## Manifest

| NAME                    | PROMPT                                    | DESCRIPTION                                             | EXAMPLE                                                                                               |
|-------------------------|-------------------------------------------|---------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| app.yaml                | YAML manifest for a Kubernetes Pod        | Defines a basic Pod resource                            | [app.yaml](./app.yaml)                          |
| app-livenessProbe.yaml  | Liveness probe for the Pod                | Configures a liveness probe for the Pod                 | [app-livenessProbe.yaml](./app-livenessProbe.yaml)   |
| app-readinessProbe.yaml | Readiness probe for the Pod               | Configures a readiness probe for the Pod                | [app-readinessProbe.yaml](./app-readinessProbe.yaml)      |
| app-volumeMounts.yaml   | Volume mounts for the Pod                 | Defines volume mounts for the Pod                       | [app-volumeMounts.yaml](./app-volumeMounts.yaml)     |
| app-cronjob.yaml        | CronJob resource for scheduling jobs      | Schedules jobs on a cron-like schedule                  | [app-cronjob.yaml](./app-cronjob.yaml  )               |
| app-job.yaml            | Job                                       | Schedules jobs on a cron-like schedule                  | [app-job.yaml](./app-job.yaml)               |
| app-multicontainer.yaml | Pod with multiple containers              | Defines a Pod with multiple containers                  | [app-multicontainer.yaml](./app-multicontainer.yaml) |
| app-resources.yaml      | Resource limits and requests for the Pod  | Configures resource limits and requests for the Pod     | [app-resources.yaml](./app-resources.yaml)           |
| app-secret-env.yaml     | Use a Secret to set environment variables | Retrieves values from a Secret as environment variables | [app-secret-env.yaml](./app-secret-env.yaml)         |

---
