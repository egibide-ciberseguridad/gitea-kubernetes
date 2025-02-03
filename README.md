# gitea-kubernetes

Instalación de [Gitea](https://about.gitea.com/products/gitea/) en Kubernetes.

## Puesta en marcha

```
kubectl apply -n ciber-99 -f https://raw.githubusercontent.com/egibide-ciberseguridad/gitea-kubernetes/master/secrets.yml
kubectl apply -n ciber-99 -f https://raw.githubusercontent.com/egibide-ciberseguridad/gitea-kubernetes/master/mariadb.yml
kubectl apply -n ciber-99 -f https://raw.githubusercontent.com/egibide-ciberseguridad/gitea-kubernetes/master/gitea.yml
```
