
- PodSecurityPolicy

    PodSecurityPolicy [устарела](https://kubernetes.io/blog/2021/04/08/kubernetes-1-21-release-announcement/#podsecuritypolicy-deprecation) в Kubernetes v1.21 и удален из Kubernetes в v1.25.
    
    PodSecurityPolicy — это ресурс на уровне кластера, который контролирует действия, которые может выполнять под, и к чему у него есть доступ. `PodSecurityPolicy` объекты определяют набор условий, которые должен выполнять под для того, чтобы быть принятым в систему. Они позволяют администратору контролировать следующее:
    https://unofficial-kubernetes.readthedocs.io/en/latest/concepts/policy/pod-security-policy/