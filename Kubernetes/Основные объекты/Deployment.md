
-  Deployment
    Deployment предоставляет декларативные обновления для [Pods](https://kubernetes.io/docs/concepts/workloads/pods/) и [ReplicaSets](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/).
    Вы описываете _желаемое состояние_ в развертывании, а [Controller](https://kubernetes.io/docs/concepts/architecture/controller/)развертывания изменяет фактическое состояние на желаемое с контролируемой скоростью. Вы можете определить развертывания для создания новых наборов реплик или для удаления существующих развертываний и использования всех их ресурсов с новыми развертываниями.
