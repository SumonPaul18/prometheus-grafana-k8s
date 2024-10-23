# Deployment Prometheus-Grafana on Kubernetes
Kubernetes Cluster Monitoring using Prometheus & Grafana
#

 199  helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
  200  helm repo update
  201  helm install my-kube-prometheus-stack prometheus-community/kube-prometheus-stack
  202  kubectl get all
  203  kubectl get pod
  204  kubectl get pod
  205  kubectl get pod
  206  kubectl get pod
  207  kubectl get pod
  208  kubectl get pod
  209  kubectl get pod
  210  kubectl describe pod prometheus-my-kube-prometheus-stack-prometheus-0
  211  kubectl get pod
  212  kubectl get pod
  213  kubectl get pod
  214  kubectl get pod
  215  kubectl get svc
  216  kubectl delete svc prometheus-server-ext
  217  kubectl expose service kube-prometheus-stack-prometheus --type=NodePort --target-port=9090 --name=prometheus-node-port-service
  218  kubectl expose service my-kube-prometheus-stack-prometheus --type=NodePort --target-port=9090 --name=prometheus-node-port-service
  219  kubectl get svc
  220  kubectl expose service kube-prometheus-stack-grafana --type=NodePort --target-port=3000 --name=grafana-node-port-service
  221  kubectl expose service my-kube-prometheus-stack-grafana --type=NodePort --target-port=3000 --name=grafana-node-port-service
  222  kubectl get svc
  223  kubectl get pv
  224  kubectl get pvc
  225  helm ls
  226  kubectl get secrets
  227  kubectl get svc
  228  ls
  229  ls
  230  helm list
  231  helm status my-kube-prometheus-stack
  232  kubectl --namespace default get pods -l "release=my-kube-prometheus-stack"
  233  kubectl get storageclasses
  234  kubectl get storageclasses -n all

#
**Reference:**

[Prometheus-Grafana Integration](https://www.bigbinary.com/blog/prometheus-and-grafana-integration)

[Install Prometheus-Grafana on Kubernetes](https://github.com/tatahnoellimnyuy/install-prometheus-and-grafana-on-kubernetes)

[Deploy Prometheus Grafana on K8s](https://gist.github.com/chadmcrowell/c9b12f32e180a6ad3dc060cdd6d63f05)

[Prometheus-Grafana NFS on K8s](https://www.fosstechnix.com/kubernetes-cluster-monitoring-with-prometheus-and-grafana/)

[]()
[]()
[]()
[]()



