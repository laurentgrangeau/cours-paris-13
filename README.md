# Cloud public

## S'enregistrer sur AWS Educate

https://aws.amazon.com/education/awseducate

## IaaS

* Créer une machine EC2
* Se connecter à la machine
* Installer un JDK, Maven et Git
* Cloner le repo Spring PetClinic : https://github.com/spring-projects/spring-petclinic
* Lancer Spring PetClinic
* Se connecter à l'application
* Obtenir une adresse IP publique
* Ouvrir le firewall
* Vérifier le bon fonctionnement

## PaaS

* Créer une instance MySQL RDS
* Suivre les instructions suivantes : https://github.com/spring-projects/spring-petclinic/blob/master/src/main/resources/db/mysql/petclinic_db_setup_mysql.txt
* Vérifier la connexion à la DB

## Bonus (Docker)
* Installer Docker sur l'instance EC2
* Créer l'image docker contenant le projet Spring PetClinic
* Faire une topologie
* Deployer la topologie sur l'instance EC2

~~~~
sudo apt remove --purge "^openjdk.*"
sudo reboot
sudo apt-get install openjdk-8-jdk
~~~~
