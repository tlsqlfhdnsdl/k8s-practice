## k8s 클러스터 구성



### k8s node 이미지 만들기

```docker build -t k8s -f k8s-node.dockerfile .```

### k8s node 컨테이너 실행



#### 마스터

```docker run -it -h k8s-master k8s bash```



#### 워커

```docker run -it -h k8s-worker1 k8s bash```

```docker run -it -h k8s-worker2 k8s bash```

