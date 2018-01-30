# Certified Kubernetes Administrator Exam Curriculum

_Version 1.9.0, January 2018_
https://github.com/cncf/curriculum/blob/master/certified_kubernetes_administrator_exam_v1.9.0.pdf
https://github.com/cncf/curriculum/

### Scheduling \[5%\]
+ [Use label selectors to schedule Pods.](https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/)
+ [Understand the role of DaemonSets.](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
+ [Understand how resource limits can affect Pod scheduling.](https://kubernetes.io/docs/concepts/policy/resource-quotas/)
+ [Understand how to run multiple schedulers and how to configure Pods to use them.](https://kubernetes.io/docs/tasks/administer-cluster/configure-multiple-schedulers/)
+ [Manually schedule a pod without a scheduler.](https://kubernetes.io/docs/tasks/administer-cluster/static-pod/)
+ [Display scheduler events.](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application-introspection/)
+ [Know how to configure the Kubernetes scheduler.](https://kubernetes.io/docs/reference/generated/kube-scheduler/)

### Logging/Monitoring \[5%\]
+ [Understand how to monitor all cluster components.](https://kubernetes.io/docs/tasks/debug-application-cluster/resource-usage-monitoring/)
+ [Understand how to monitor applications.](http://blog.kubernetes.io/2017/05/kubernetes-monitoring-guide.html)
+ [Manage cluster component logs.](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-cluster/)
+ [Manage application logs.](https://kubernetes.io/docs/concepts/cluster-administration/logging/)

### Application Lifecycle Management \[8%\]
+ [Understand Deployments and how to perform rolling updates and rollbacks.](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
+ [Know various ways to configure applications.](https://kubernetes.io/docs/tutorials/kubernetes-basics/deploy-intro/)
+ [Know how to scale applications.](https://kubernetes.io/docs/tasks/run-application/scale-stateful-set/)
+ [Understand the primitives necessary to create a self-healing application.](https://12factor.net/)

### Cluster Maintenance \[11%\]
+ Understand Kubernetes cluster upgrade process.
  + [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-upgrade/)
  + [Canonical Distribution of Kubernetes](https://kubernetes.io/docs/getting-started-guides/ubuntu/upgrades/)
+ [Facilitate operating system upgrades.]()
+ [Implement backup and restore methodologies.](https://kubernetes.io/docs/getting-started-guides/ubuntu/backups/)

### Security \[12%\]
+ Know how to configure [authentication](https://kubernetes.io/docs/admin/authentication/) and [authorization](https://kubernetes.io/docs/admin/authorization/).
+ [Understand Kubernetes security primitives.]()
+ [Know to configure network policies.](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
+ [Create and manage TLS certificates for cluster components.](https://kubernetes.io/docs/tasks/tls/managing-tls-in-a-cluster/)
+ [Work with images securely.](https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/)
+ [Define security contexts.](https://kubernetes.io/docs/tasks/configure-pod-container/security-context/)
+ [Secure persistent key value store.](https://kubernetes.io/docs/tasks/administer-cluster/configure-upgrade-etcd/)
+ [Work with role-based access control.](https://kubernetes.io/docs/admin/authorization/rbac/)

### Storage \[7%\]
+ [Understand persistent volumes and know how to create them.](https://kubernetes.io/docs/concepts/storage/persistent-volumes/)
+ [Understand access modes for volumes.](https://kubernetes.io/docs/concepts/storage/persistent-volumes/#access-modes-1)
+ [Understand persistent volume claims primitive.](https://kubernetes.io/docs/concepts/storage/persistent-volumes/#persistentvolumeclaims)
+ [Understand Kubernetes storage objects.](https://kubernetes.io/docs/concepts/storage/volumes/)
+ [Know how to configure applications with persistent storage.](https://kubernetes.io/docs/tasks/configure-pod-container/configure-persistent-volume-storage/)

### Troubleshooting \[10%\]
+ [Troubleshoot application failure.](https://kubernetes.io/docs/tasks/debug-application-cluster/determine-reason-pod-failure/)
+ [Troubleshoot control plane failure.](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-cluster/)
+ [Troubleshoot worker node failure.](https://kubernetes.io/docs/tasks/debug-application-cluster/monitor-node-health/)
+ [Troubleshoot networking.]()

### Core Concepts \[19%\]
+ [Understand the Kubernetes API primitives.](https://kubernetes.io/docs/concepts/overview/kubernetes-api/)
+ [Understand the Kubernetes cluster architecture.](https://kubernetes.io/docs/concepts/overview/components/)
+ [Understand Services and other network primitives.](https://kubernetes.io/docs/concepts/services-networking/service/)

### Networking \[11%\]
+ [Understand the networking configuration on the cluster nodes.](https://kubernetes.io/docs/concepts/cluster-administration/networking/)
+ [Understand Pod networking concepts.]()
+ [Understand service networking.](https://kubernetes.io/docs/concepts/services-networking/service/)
+ [Deploy and configure network load balancer.](https://kubernetes.io/docs/tasks/access-application-cluster/create-external-load-balancer/)
+ [Know how to use Ingress rules.](https://kubernetes.io/docs/concepts/services-networking/ingress/)
+ [Know how to configure and use the cluster DNS.](https://kubernetes.io/docs/tasks/administer-cluster/dns-custom-nameservers/)
+ [Understand CNI.](https://kubernetes.io/docs/concepts/cluster-administration/network-plugins/)

### Installation, Configuration & Validation \[12%\]
+ [Design a Kubernetes cluster.](https://kubernetes.io/docs/getting-started-guides/scratch/)
+ [Install Kubernetes masters and nodes, including the use of TLS bootstrapping.](https://kubernetes.io/docs/getting-started-guides/scratch/)
+ [Configure secure cluster communications.](https://kubernetes.io/docs/tasks/administer-cluster/securing-a-cluster/)
+ [Configure a Highly-Available Kubernetes cluster.](https://kubernetes.io/docs/admin/high-availability/)
+ [Know where to get the Kubernetes release binaries.](https://kubernetes.io/docs/getting-started-guides/scratch/#downloading-and-extracting-kubernetes-binaries)
+ [Provision underlying infrastructure to deploy a Kubernetes cluster.]()
+ [Choose a network solution.](https://kubernetes.io/docs/getting-started-guides/scratch/#network)
+ [Choose your Kubernetes infrastructure configuration.](https://kubernetes.io/docs/setup/pick-right-solution/)
+ [Run end-to-end tests on your cluster.](https://kubernetes.io/docs/getting-started-guides/ubuntu/validation/)
+ [Analyse end-to-end tests results.]()
+ [Run Node end-to-end tests.](https://kubernetes.io/docs/admin/node-conformance/)
