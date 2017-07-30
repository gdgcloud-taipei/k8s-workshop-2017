# Kubernetes Workshop

## 活動頁面

https://gcpugtw.kktix.cc/events/meetup201708-workshop

## 行前通知

此課程建議事先安裝 minikube ，或者已經有 GCP 開啟 Google Container Engine 也可以，其中 minikube 請參考官方文件以及您自己的環境安裝：

```
https://github.com/kubernetes/minikube
```

另外，kubectl 這個 requirement 可以直接 “gcloud components install kubectl"

## 確認環境

使用 minibuke 或者 GCP 都請確認你們的環境可以跑到

```
kubectl run nginx --image=nginx --port=80
kubectl get pods
```

有跑出 pod 來，然後刪除掉剛剛開的 deployment

```
kubectl delete deploy/nginx
```

也可以跑一下 “minikube dashboard” 看一下 minikube 的 dashboard

## Workshop 1 - 概念與K8S基本架構

### 課程內容

介紹K8S的基本概念與架構，帶大家手把手玩K8S＾＾，請參加者攜帶電腦並自備網路！

### 時間

20170804 15:00 - 16:00 

## Workshop 2 - GKE上運作您的K8S服務

從K8S到Google GKE，讓您一步上雲端＾＾，請參加者攜帶電腦並自備網路！

### 時間

20170804 16:30 - 17:30 
