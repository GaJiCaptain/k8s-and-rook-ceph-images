# k8s-and-rook-ceph-images
install k8s and rook-ceph docker images


```bash
docker pull k8s.gcr.io/kube-apiserver:v1.21.3
docker pull k8s.gcr.io/kube-controller-manager:v1.21.3
docker pull k8s.gcr.io/kube-scheduler:v1.21.3
docker pull k8s.gcr.io/kube-proxy:v1.21.3
docker pull k8s.gcr.io/pause:3.4.1
docker pull k8s.gcr.io/etcd:3.4.13-0
docker pull k8s.gcr.io/coredns/coredns:v1.8.0
```
registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns
```bash
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.21.3
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.21.3
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.21.3
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.21.3
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.4.1
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.4.13-0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.0

sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.21.3 k8s.gcr.io/kube-apiserver:v1.21.3
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.21.3 k8s.gcr.io/kube-controller-manager:v1.21.3
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.21.3 k8s.gcr.io/kube-scheduler:v1.21.3
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.21.3 k8s.gcr.io/kube-proxy:v1.21.3
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.4.1 k8s.gcr.io/pause:3.4.1
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.4.13-0 k8s.gcr.io/etcd:3.4.13-0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.0 k8s.gcr.io/coredns/coredns:v1.8.0

sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.21.3
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.21.3
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.21.3
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.21.3
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.4.1
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.4.13-0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.0


```