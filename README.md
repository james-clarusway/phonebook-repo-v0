```bash
helm repo add phonebook-repo https://raw.githubusercontent.com/james-clarusway/phonebook-repo/main
helm install pb-app phonebook-repo
```

- To use own images execute as below:

```bash
helm install pb-app phonebook-repo --set webserver_image=<image-name> --set resultserver_image=<image-name>
```