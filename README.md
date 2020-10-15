#Curso Full Cycle
##Utilizando K8S

##### Autor: [Rafael Camoleze](mailto:contato@rafaelcamoleze.com)

1. Servidor Web Nginx / Kubernetes

    Repo Folder: [nginx](nginx) | [Load Balancer no GCP](http://34.122.8.202/)
    
2. Configuração MySQL / Kubernetes

    Repo Folder: [mysql](mysql)
   
3. Desafio Go
   1. Aplicativo webserver em Go | Repo Folder: [desafio-go](desafio-go/src/desafio-go)
   2. Trigger de CI para cada PR | File build & test [cloudbuid.yaml](desafio-go/cloudbuild.yaml)
   3. Imagem publicada no Docker Hub | [Link Docker Hub](https://hub.docker.com/r/camolezerafael/desafio-go-webserver-greeting)
   4. Load Balancer webserver em Go no GCP | [Load Balancer no GCP](http://104.154.134.235/)

4. Desafio Go _(Informações Adicionais)_
    1. Criado um repositório exclusivo para o projeto Go
    2. [Link do Repositório](https://github.com/camolezerafael/k8s-desafio-go)
    3. Neste repositório estão configurados:
        1. Trigger CI para cada Pull Request
        2. Publicação automatizada da Imagem no Docker Hub para cada push no branch master
