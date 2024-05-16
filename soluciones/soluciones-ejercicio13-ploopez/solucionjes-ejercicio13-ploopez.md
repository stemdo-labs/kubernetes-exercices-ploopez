Primero creamos el index.html

Luego creamos el configmap con el siguiente comando :
    kubectl create configmap index-configmap --from-file=index.html

![alt text](image.png)

Después  creamos  el deployment y el service

Ejecutamos el siguiente comando:
    minikube service webserver-service

![alt text](image-1.png)

Y en el navegador se ve asi:

![alt text](image-2.png)

