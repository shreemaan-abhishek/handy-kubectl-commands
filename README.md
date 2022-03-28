# handy-kubectl-commands

_although it's ironic that the very first command isn't a `kubectl` command, but you get the idea about why this repository exists._

| Command | Description |
| ------- | ----------- |
| `minikube service <service-name>` | Starts a tunnel for the given service and opens it in default browser. |
| `kubectl get all --all-namespaces` | Lists everything	|
| `kubectl get pods -n <pod-name> --watch` | watches the given pod |
| `kubectl expose deployment <dep-name> --type=LoadBalancer --name=my-service` | Creates a service object that exposes the deployment | 
| `kubectl config set-context --current --namespace=my-namespace` | Switch to `my-namespace` |
| `kubectl get <resource> -o=yaml` | Get the output of a resource as yaml |
