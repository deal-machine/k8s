<br>

<div align="center">


<br>

<span>
<img width="150" src="https://user-images.githubusercontent.com/25181517/182534006-037f08b5-8e7b-4e5f-96b6-5d2a5558fa85.png" />
</span>
</div>
<br>


</div>
<div align="right">
<a href="https://kubernetes.io/">kubernetes.io</a>
</div>
<br>

<div align="center">
  <h3>Components</h3>
  
<img src="https://kubernetes.io/images/docs/components-of-kubernetes.svg" />

</div>
<br>
<div align="center">
<h3>Architecture</h3>
<img src="https://kubernetes.io/images/docs/kubernetes-cluster-architecture.svg" />
</div>
<br>

## Commands

```bash
# create namespace
$ kubectl create namespace [namespace-name]

# set namespace to default
$ kubectl config set-context --current --namespace=[namespace-name]

# show nodes
$ kubectl get nodes -o wide

# show pods
$ kubectl get pods

# show services
$ kubectl get svc -o wide

# show configmaps
$ kubectl get configmap

# show pod description 
$ kubectl describe pod [pod-name]

# show pod logs
$ kubectl logs [pod-name] --follow

# apply yaml file or folder
$ kubectl apply -f k8s/file.yaml

# destroy yaml file or folder
$ kubectl destroy -f k8s/

# to watch all pods running
$ watch -n1 kubectl get pods
```
