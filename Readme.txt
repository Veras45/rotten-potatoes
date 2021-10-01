1- Criar o Cluster usando o comando, dentro da pasta rotten-potatoes 
kind create cluster --name meucluster --config cluster.yaml

Valide se o cluster foi criado usando:
kind get clusters

2 - acesse a pasta k8s, e crie o deployment com o comando: 
kubectl apply -f meudeployment.yaml

valide se foi criado usando 

kubectl get pods ou kubectl get all 

apos isso sua aplicacao ja vai esta no ar! 


OBS: Necessario ter a image no seu DockerHub... 


