```shell
git clone https://github.com/philschmid/faas-netes-oseven

cd faas-netes-oseven

make build


# connect to shell in pod

 kubectl exec -it mongodb-744f8f5d4-k24j8  -n openfaas-db sh
```
