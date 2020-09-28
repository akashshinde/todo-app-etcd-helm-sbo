## Introduction
This is a Helm chart which install following things.
-  Deploys Todo NodeJS application.
-  Deploys Etcd Cluster.
-  Creates Service Binding CR to bind EtcdCluster to NodeJS Todo App.

Please refer for more details: [Bind Etcd Application](https://github.com/redhat-developer/service-binding-operator/blob/master/examples/nodejs_etcd_operator/README.md)

## How
#### Clone the repository

```shell script
 git clone https://github.com/akashshinde/todo-app-etcd-helm-sbo
```

#### Install Helm chart

```shell script
helm install --generate-name todo-app-etcd-helm-sbo
```

Once helm chart is deployed, you should see Route created and application deployed.

