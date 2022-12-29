# pgadmin


![Version: 1.0.0](https://img.shields.io/badge/Version-1.0.0-informational?style=flat-square)  ![AppVersion: 1.0](https://img.shields.io/badge/AppVersion-1.0-informational?style=flat-square) 

## Description

pgAdmin is a web based administration tool for the PostgreSQL database.



## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| VolumePermissions.enabled | bool | `false` |  |
| affinity | object | `{}` |  |
| annotations | object | `{}` |  |
| autoscaling.enabled | bool | `false` |  |
| autoscaling.maxReplicas | int | `100` |  |
| autoscaling.minReplicas | int | `1` |  |
| autoscaling.targetCPUUtilizationPercentage | int | `80` |  |
| containerPorts.http | int | `80` |  |
| containerSecurityContext.allowPrivilegeEscalation | bool | `false` |  |
| containerSecurityContext.enabled | bool | `false` |  |
| env.email | string | `"abhi@domain.com"` |  |
| env.enhanced_cookie_protection | string | `"False"` |  |
| env.password | string | `"Abhi@101299"` |  |
| env.variables | list | `[]` |  |
| existingSecret | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.registry | string | `"docker.io"` |  |
| image.repository | string | `"dpage/pgadmin4"` |  |
| image.tag | string | `"6.18"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0].host | string | `"chart-example.local"` |  |
| ingress.hosts[0].paths[0].path | string | `"/"` |  |
| ingress.hosts[0].paths[0].pathType | string | `"Prefix"` |  |
| ingress.tls | list | `[]` |  |
| init.resources | object | `{}` |  |
| istio.authorizationPolicy.allowedNaemspaces | list | `[]` |  |
| istio.authorizationPolicy.enabled | bool | `false` |  |
| istio.destinationRule.enabled | bool | `false` |  |
| istio.enabled | bool | `false` |  |
| istio.gateway.enabled | bool | `true` |  |
| istio.gateway.ingressHost | string | `"*"` |  |
| istio.gateway.portName | string | `"http"` |  |
| istio.gateway.portNumber | int | `80` |  |
| istio.gateway.protocol | string | `"HTTP"` |  |
| istio.virtualService.enabled | bool | `true` |  |
| istio.virtualService.gateway | string | `"pgadmin"` |  |
| istio.virtualService.host | string | `"*"` |  |
| istio.virtualService.route[0].destination | string | `nil` |  |
| istio.virtualService.route[0].host | string | `"pgadmin.pgadmin.svc.cluster.local"` |  |
| istio.virtualService.route[0].port.number | int | `8080` |  |
| istio.virtualService.timeout | string | `"1m"` |  |
| istio.virtualService.uriPrefix[0] | string | `"/"` |  |
| livenessProbe.failureThreshold | int | `3` |  |
| livenessProbe.initialDelaySeconds | int | `30` |  |
| livenessProbe.periodSeconds | int | `60` |  |
| livenessProbe.successThreshold | int | `1` |  |
| livenessProbe.timeoutSeconds | int | `15` |  |
| networkPolicy.enabled | bool | `true` |  |
| nodeSelector | object | `{}` |  |
| persistentVolume.accessModes[0] | string | `"ReadWriteOnce"` |  |
| persistentVolume.annotations | object | `{}` |  |
| persistentVolume.enabled | bool | `true` |  |
| persistentVolume.size | string | `"10Gi"` |  |
| podAnnotations | object | `{}` |  |
| podLabels | object | `{}` |  |
| readinessProbe.failureThreshold | int | `3` |  |
| readinessProbe.initialDelaySeconds | int | `30` |  |
| readinessProbe.periodSeconds | int | `60` |  |
| readinessProbe.successThreshold | int | `1` |  |
| readinessProbe.timeoutSeconds | int | `15` |  |
| replicaCount | int | `1` |  |
| resources.limits.cpu | string | `"100m"` |  |
| resources.limits.memory | string | `"128Mi"` |  |
| resources.requests.cpu | string | `"50m"` |  |
| resources.requests.memory | string | `"64Mi"` |  |
| secretKeys.pgadminPasswordKey | string | `"password"` |  |
| securityContext.fsGroup | int | `5050` |  |
| securityContext.runAsGroup | int | `5050` |  |
| securityContext.runAsUser | int | `5050` |  |
| serverDefinitions.enabled | bool | `false` |  |
| service.annotations | object | `{}` |  |
| service.clusterIP | string | `""` |  |
| service.loadBalancerIP | string | `""` |  |
| service.port | int | `8080` |  |
| service.portName | string | `"http"` |  |
| service.targetPort | int | `80` |  |
| service.type | string | `"ClusterIP"` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `false` |  |
| serviceAccount.name | string | `""` |  |
| tolerations | list | `[]` |  |