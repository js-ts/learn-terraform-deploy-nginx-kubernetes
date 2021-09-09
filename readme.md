# This is the code from this [tutorial](https://learn.hashicorp.com/tutorials/terraform/kubernetes-provider?in=terraform/kubernetes)

when i run 
```
terraform apply
```
```
Do you want to perform these actions?
  Terraform will perform the actions described above.
  Only 'yes' will be accepted to approve.

  Enter a value: yes

kubernetes_deployment.nginx: Creating...
kubernetes_deployment.nginx: Still creating... [10s elapsed]
kubernetes_deployment.nginx: Still creating... [20s elapsed]
kubernetes_deployment.nginx: Still creating... [30s elapsed]
kubernetes_deployment.nginx: Still creating... [40s elapsed]
kubernetes_deployment.nginx: Still creating... [50s elapsed]
kubernetes_deployment.nginx: Still creating... [1m0s elapsed]
kubernetes_deployment.nginx: Still creating... [1m10s elapsed]
kubernetes_deployment.nginx: Still creating... [1m20s elapsed]
kubernetes_deployment.nginx: Still creating... [1m30s elapsed]
kubernetes_deployment.nginx: Still creating... [1m40s elapsed]
kubernetes_deployment.nginx: Still creating... [1m50s elapsed]
kubernetes_deployment.nginx: Still creating... [2m0s elapsed]
kubernetes_deployment.nginx: Still creating... [2m10s elapsed]
kubernetes_deployment.nginx: Still creating... [2m20s elapsed]
kubernetes_deployment.nginx: Still creating... [2m30s elapsed]
kubernetes_deployment.nginx: Still creating... [2m40s elapsed]
kubernetes_deployment.nginx: Still creating... [2m51s elapsed]
kubernetes_deployment.nginx: Still creating... [3m1s elapsed]
kubernetes_deployment.nginx: Still creating... [3m11s elapsed]
kubernetes_deployment.nginx: Still creating... [3m21s elapsed]
kubernetes_deployment.nginx: Still creating... [3m31s elapsed]
kubernetes_deployment.nginx: Still creating... [3m41s elapsed]
kubernetes_deployment.nginx: Still creating... [3m51s elapsed]
kubernetes_deployment.nginx: Still creating... [4m1s elapsed]
kubernetes_deployment.nginx: Still creating... [4m11s elapsed]
kubernetes_deployment.nginx: Still creating... [4m21s elapsed]
kubernetes_deployment.nginx: Still creating... [4m31s elapsed]
kubernetes_deployment.nginx: Still creating... [4m41s elapsed]
kubernetes_deployment.nginx: Still creating... [4m51s elapsed]
kubernetes_deployment.nginx: Still creating... [5m1s elapsed]
kubernetes_deployment.nginx: Still creating... [5m11s elapsed]
kubernetes_deployment.nginx: Still creating... [5m21s elapsed]
kubernetes_deployment.nginx: Still creating... [5m31s elapsed]
kubernetes_deployment.nginx: Still creating... [5m41s elapsed]
kubernetes_deployment.nginx: Still creating... [5m51s elapsed]
kubernetes_deployment.nginx: Still creating... [6m1s elapsed]
kubernetes_deployment.nginx: Still creating... [6m11s elapsed]
kubernetes_deployment.nginx: Still creating... [6m21s elapsed]
kubernetes_deployment.nginx: Still creating... [6m31s elapsed]
kubernetes_deployment.nginx: Still creating... [6m41s elapsed]
kubernetes_deployment.nginx: Still creating... [6m51s elapsed]
kubernetes_deployment.nginx: Still creating... [7m1s elapsed]
kubernetes_deployment.nginx: Still creating... [7m11s elapsed]
kubernetes_deployment.nginx: Still creating... [7m21s elapsed]
kubernetes_deployment.nginx: Still creating... [7m31s elapsed]
kubernetes_deployment.nginx: Still creating... [7m41s elapsed]
kubernetes_deployment.nginx: Still creating... [7m51s elapsed]
kubernetes_deployment.nginx: Still creating... [8m1s elapsed]
kubernetes_deployment.nginx: Still creating... [8m11s elapsed]
kubernetes_deployment.nginx: Still creating... [8m21s elapsed]
kubernetes_deployment.nginx: Still creating... [8m31s elapsed]
kubernetes_deployment.nginx: Still creating... [8m41s elapsed]
kubernetes_deployment.nginx: Still creating... [8m51s elapsed]
kubernetes_deployment.nginx: Still creating... [9m1s elapsed]
kubernetes_deployment.nginx: Still creating... [9m11s elapsed]
kubernetes_deployment.nginx: Still creating... [9m21s elapsed]
kubernetes_deployment.nginx: Still creating... [9m31s elapsed]
kubernetes_deployment.nginx: Still creating... [9m41s elapsed]
kubernetes_deployment.nginx: Still creating... [9m51s elapsed]
╷
│ Error: Waiting for rollout to finish: 2 replicas wanted; 0 replicas Ready
│
│   with kubernetes_deployment.nginx,
│   on kubernetes.tf line 33, in resource "kubernetes_deployment" "nginx":
│   33: resource "kubernetes_deployment" "nginx" {
│
╵
```

this error appears can anybody suggest a solution ,I'm running this on my local machine using kind