# Kubernetes (K8s)
<img src="https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png" alt="drawing" width="100"/>
Esse repositório tem como objetivo mostrar como subir uma aplicação Wordpress + DB Mysql utilizando kubernetes.

# Requisitos necessários para execução dessa atividade:

-  Instalar o docker desktop. https://docs.docker.com/desktop/install/windows-install/
-  Instalar o kubectl.
-  Instalar o minikube. 
-  Verificar Wsl e o Hiper-V.

# Usando o Rancher:

- Abra o terminal do Ubuntu ou o powershell se estiver usando o Windows.

Digite: ```docker run -d --name rancher --restart=unless-stopped -v /opt/rancher:/var/lib/rancher  -p 80:80 -p 443:443 rancher/rancher:v2.4.3```

- Após, abra um navegador e digite :  ```localhost:80```.

- Feito isso estará dentro do Rancher.








