```
echo "# K8s_respository" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/j99d99/K8s_respository.git
git push -u origin master

xxxxxxxxxxxxxxxxxxxxxx

git remote add origin https://github.com/j99d99/K8s_respository.git
git push -u origin master

docker pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v1.3.1
docker pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v3.1
docker pull pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v3.3.10
dcoker pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v1.15.0
docker pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:1.15.2
docker pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:1.15.0
docker pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:1.15.1

docker tag registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v1.3.1 k8s.gcr.io/coredns:1.3.1
docker tag registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v3.1 k8s.gcr.io/pause:3.1
docker tag pull registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v3.3.10 k8s.gcr.io/etcd:3.3.10
dcoker tag registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:v1.15.0 k8s.gcr.io/kube-controller-manager:v1.15.0
docker tag registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:1.15.2 k8s.gcr.io/kube-scheduler:v1.15.0
docker tag registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:1.15.0 k8s.gcr.io/kube-apiserver:v1.15.0
docker tag registry.cn-hangzhou.aliyuncs.com/mj_k8s/k8s:1.15.1 k8s.gcr.io/kube-proxy:v1.15.0
```
