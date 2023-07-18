# Projet terraform :

le but est de déployer une insfrastructure complète 
création de l'instance EC2/AWS utilisant la dernière version Ubuntu bionic ( qui s'attachera à l'EBS et Ip publique ) dont la taille et le tag seront verbailisés
![ec2apply](https://github.com/mikimihia/terraform/assets/44511981/93970249-2ef0-439e-926d-6019283463f9)

un module pour créer un volume ebs dont la taille sera variabilisée
un module pour une ip publique (qui s’attachera la security group)
![aws_accueil](https://github.com/mikimihia/terraform/assets/44511981/b35b142b-085e-4620-a01a-577232632b65)
Ecrivez un module pour créer une security qui ouvrira le 80 et 443
![ebs_aws](https://github.com/mikimihia/terraform/assets/44511981/428cf718-2da5-4e5c-b2aa-ab0fafc9fce4)
![securty_group](https://github.com/mikimihia/terraform/assets/44511981/77992fa0-d4b5-47a2-98af-0b610f00e936)
![securty_group](https://github.com/mikimihia/terraform/assets/44511981/b71f16b7-9798-46cf-b7fe-1923e08e07e1)
![ip_ec2](https://github.com/mikimihia/terraform/assets/44511981/538dd83c-769d-423d-aa7c-961f32a7067e)


les 4 modules pour déployer une ec2, bien-sûr vous allez surcharger

