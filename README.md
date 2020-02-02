# Kebab_ar

## Pré requis

Il est préférable de tester notre application sur mobile

## Installation en local
lancer la commande pour telecharger les packets node
```
npm start   
```

dans un premier terminal lancer ngrok avec la commande : 
```
ngrok http 8080 -host-header="localhost:8080"
```

dans un second terminal lancer le serveur node avec la commande:
```
npm start
```

## Utiliser le serveur Github
se rendre sur l'url

https://blinkix.github.io/Kebab_ar/


## L'application

il s'agit d'une application en Node Js permettant de recupérer et d'afficher les fast food a proximité.

Dans l'application, SOS Kebab on choisit le type de nourriture que l'on veut manger.

* En réalité le choix est illusoire car nous n'avons pas eu le temps de le faire 

Il faut alors autoriser la caméra et la localisation

***Attention***

L'api étant gratuite, est assez lente et le temps de recuperer les infos peut durer 35 - 40 secondes  


L'api utilisé est celle de open street map


## Membres du groupe

* Seyaret Adryen
* Calvet Bastien
* Ville Julien
* Ehrel Arthur
* Kerihuel Meven 