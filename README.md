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

FROM k8s.gcr.io/sig-storage/csi-provisioner:v2.2.2
FROM k8s.gcr.io/sig-storage/csi-snapshotter:v4.1.1
FROM k8s.gcr.io/sig-storage/csi-attacher:v3.2.1
FROM k8s.gcr.io/sig-storage/csi-resizer:v1.2.0
FROM k8s.gcr.io/sig-storage/csi-node-driver-registrar:v2.2.0
FROM quay.io/cephcsi/cephcsi:v3.3.1
FROM rook/ceph:v1.6.8
FROM ceph/ceph:v15.2.13
```

```bash
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.22.0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.5
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.5.0-0
sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.4

sudo docker pull registry.cn-hangzhou.aliyuncs.com/gajicaptain/ceph:v1.6.8


sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.22.0 k8s.gcr.io/kube-apiserver:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.22.0 k8s.gcr.io/kube-controller-manager:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.22.0 k8s.gcr.io/kube-scheduler:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.22.0 k8s.gcr.io/kube-proxy:v1.22.0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.5 k8s.gcr.io/pause:3.5
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.5.0-0 k8s.gcr.io/etcd:3.5.0-0
sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.4 k8s.gcr.io/coredns/coredns:v1.8.4

sudo docker tag registry.cn-hangzhou.aliyuncs.com/gajicaptain/ceph:v1.6.8  rook/ceph:v1.6.8

sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-apiserver:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-controller-manager:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-scheduler:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/kube-proxy:v1.22.0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/pause:3.5
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/etcd:3.5.0-0
sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/coredns:v1.8.4

sudo docker rmi registry.cn-hangzhou.aliyuncs.com/gajicaptain/ceph:v1.6.8
```