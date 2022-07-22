# Kind

- install

```
$ curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.14.0/kind-linux-amd64
$ chmod +x ./kind

$ sudo mv ./kind /usr/local/bin/kind

$ kind --version
kind version 0.14.0
```

```
$ kind create cluster --name pmc
```

```
$ kind delete cluster --name pmc
```
