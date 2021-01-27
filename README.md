Deploy Cassandra operator on namespace cass-operator
kubectl create -f https://raw.githubusercontent.com/datastax/cass-operator/v1.5.1/docs/user/cass-operator-manifests-v1.16.yaml

Storage classes
https://github.com/datastax/cass-operator/tree/master/operator/k8s-flavors

For minikube (same as minikube default sc):
kubectl create -f https://raw.githubusercontent.com/datastax/cass-operator/master/operator/k8s-flavors/minikube/storage.yaml




