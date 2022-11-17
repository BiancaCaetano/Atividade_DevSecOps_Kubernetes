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

# O que você precisará para instalar o minikube:
- 2 CPUs ou mais
- 2 GB de memória livre
- 20 GB de espaço livre em disco
- conexão de internet
- Gerenciador de contêiner ou máquina virtual, como: Docker , Hyperkit , Hyper-V , KVM , Parallels , Podman , VirtualBox ou VMware Fusion/Workstation

- No linux ubuntu: 

- Vá até o terminal e digite : ``` curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube ```








