![alt text](image.png)

<!-- Commande - Docker info -->
![alt text](image-1.png)

<!-- Commande - Docker ps -->
![alt text](image-2.png)

<!-- Commande - Docker images -->
![alt text](image-3.png)

<!-- Commande - Docker Run -->
![alt text](image-4.png)

<!-- Commande - Docker Stop -->
![alt text](image-5.png)

<!-- Commande - Docker pull -->
![alt text](image-6.png)

<!-- Commande - Docker images -->
![alt text](image-7.png)

<!-- Commande - Docker run welcome to docker -->
![alt text](image-8.png)

<!-- Commande - Docker stop id (docker stop 7a2f5efde586) -->
![alt text](image-9.png)

<!-- Commande - Docker Supprimez r (docker rm -f <id conteneur) -->
![alt text](image-11.png)

<!-- Commande - Docker Supprimez Image (docker rmi <id conteneur) -->
![alt text](image-12.png)

<!-- Supprimer les images  -->
docker rmi $(docker images -a -q)

<!-- Supprimez un conteneur specifique  -->
docker rm nom_ou_id_conteneur

<!-- Supprimez plusieurs connteurs  -->
docker rm conteneur1 conteneur2 conteneur3

<!-- Supprimez tous les containeurs inutilisé -->
docker container  prune

<!-- Supprimez un docker actif  -->
docker rm -f nom_ou_id_conteneur

