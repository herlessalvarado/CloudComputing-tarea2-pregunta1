# Cloud Computing - Tarea 2

## Pregunta 1

1.1 Crear un cluster kubernetes local con un único nodo (host, vm, containers).

```
$ minikube start
```
![alt text](/start-1-nodo.png)


```
$ kubectl cluster-info
```
![alt text](/1-nodo-info.png)

```
kubectl get nodes -owide
```
![alt text](/1-nodo-nodes.png)


1.2 Crear un cluster kubernetes local multi-nodo (host, vm, containers). Por lo menos 2 nodos.

```
$ minikube start --nodes 2 -p multinode-demo
```
![alt text](/start-2-nodo.png)


```
$ kubectl cluster-info
```
![alt text](/2-nodo-info.png)

```
kubectl get nodes -owide
```
![alt text](/2-nodo-nodes.png)
