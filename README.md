# k8s-and-rook-ceph-images
install k8s and rook-ceph docker images


```bash
docker pull k8s.gcr.io/kube-apiserver:v1.22.0
docker pull k8s.gcr.io/kube-controller-manager:v1.22.0
docker pull k8s.gcr.io/kube-scheduler:v1.22.0
docker pull k8s.gcr.io/kube-proxy:v1.22.0
docker pull k8s.gcr.io/pause:3.5
docker pull k8s.gcr.io/etcd:3.5.0-0
docker pull k8s.gcr.io/coredns/coredns:v1.8.4
docker pull quay.io/coreos/flannel:v0.14.0
```

```bash
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.5
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.5.0-0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.4
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/flannel:v0.14.0

sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.22.0 k8s.gcr.io/kube-apiserver:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.22.0 k8s.gcr.io/kube-controller-manager:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.22.0 k8s.gcr.io/kube-scheduler:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.22.0 k8s.gcr.io/kube-proxy:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.5 k8s.gcr.io/pause:3.5
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.5.0-0 k8s.gcr.io/etcd:3.5.0-0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.4 k8s.gcr.io/coredns/coredns:v1.8.4
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/flannel:v0.14.0 quay.io/coreos/flannel:v0.14.0

sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.5
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.5.0-0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.4
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/flannel:v0.14.0

```