# Kubernetes-infinispancluster
Cluster for Infinispan in Kubernetes

after execute yaml use  below command open infinispan admin console or you can expose ports in service also here me expose port manually.

kubectl expose deployment infinispan-server --type=LoadBalancer --port 9990 --target-port 9990
