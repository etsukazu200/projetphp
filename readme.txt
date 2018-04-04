projet php

bravo  vasy

31/03/2018:

définition " webmaster " :

le webmaster est le propriétaire du site

il existe deux type des sites :

sites statiques : se sont des sites realisés à l'aide du "HTML" et "CSS" sans qu'il y'aura 
              de mise à jours au niveau des données sauf lors d'un nouveau changement de code source,ils sont utilisés 
     utilisés comme site "vitrine" pour présenter une entreprise par exp.

sites dynamiques : ils peuvent créer à l'aide d'autre langagues à part le HTML et CSS tel que le php et MYSQL
        leur contenue se mis à jour automatiquement sans l'intervention du webmaster.
l'objectif du cour est d'apprendre à faire :
des forums  , compteur de visiteurs qui visite le site, envoyer une lettre à tt les utilisateurs du site...

###################  tres bien bonne continuation    ########################################


01/04/2018 :

Définition d Internet :
l internet est un reseau composé d'ordinateurs qui se partagent en 2 categories :

les clients : se sont les ordinateurs des internautes ( les visiteurs des sites web) qui tape en realité l'adresse du site web dans le navigateur
pour demander au serveur de lui délivrer le site 


les serveurs : se sont les ordinateurs puissants qui stockent et  fournissent les site web ( page web ) demandées par les clients,ils travaillent sans
  arréts 24h/24h, 7jours/7jours .sans l'intervention humaine .

le fonctionnement/Transfére entre client-serveur se différent celon le type du site web (statique ou dynamique ) .
1.Transfertavec un site statique :
pour les sites web statiques les choses sont plus simples ils se basent sur une demande à voir le site au serveur, ensuite ce dernier ( le serveur ) répond le client
en lui délivrant la page wéb/site statique sans la modifier .

2.Transfert avec un site dynamique:

1) demande de la page web dynamique  par le client ,2) géneration de la page web par le serveur ce qui rend celle-ci changeable= dynamique

 à chaque instant ( à chaque nouveau génertion ),3)envoie de la page web dynamique  par le serveurs.

02/04/2018 :

lorsque le serveur envoie la page web au client en réalité il envoie le code source en html et css .

pour un site statique :on a le HTML et CSS .


html : est un langague à la base de la creation des sites web il contient des balises .
exple : pour écrire un texte/paragraphe on fait <p> jilali  </p>


css : c 'est un langague de mise en forme du site web il s'occupe de la mise en page et choix des couleurs 
et la taille  du menu .


pour un site dynamique : on ajoute le php et MYSQL:

php : est un langague que seulment les serveurs le comprennent et qu'il génere les pages web envoyer aux clients

exmple :  afficher le nombre de visiteur : <php? "vous étes le visiteur n° ".&nombre_visiteur;? >


MYSQL:  c'est un systéme de gestion de bases de données (SGBD), il aide à stocker/enregistrer et orgniser touts les données,listes des visiteurs,les msgs,les commentaires ayant 
  apparues dans le site,
SQL: le langague qui permet de communiquer avec la base de données.

le php et MYSQL doivent étre combiner pour que les choses marche bien . 

le php génere le HTML qui sera envoyé au client qui est  incapable de comprendre le php raison de plus pour lui envoyer le html ( et aussi le css rarment ).


 plusiers combinaisons sont possible:

le php peut étre combiné avec d'autre systéme de gestion de base de données tel que "oracle" et "postgreSQL" 
de méme MYSQL peut étre utilisé avec d'autre langague ( java;phyton,ruby ).


Les concurents de php :

ASP.NET:conçu pr microsoft il exploite un framework ( des bibliothéques qui réservent des services aux dévloppeurs qu'il sont habituller de travailler 

avec le#c
ruby on rails : c 'est un framework permet de créer des sites dynamiques rapidement il fonctionne avec le langague ruby.

Django : il est similire à ruby on rails , mais  utilise le langague python.

java et jsp ( java server page ): plus professionnel il est long  pour faire un projet avec .


les concurents de MYSQL :


Oracle :trops cher , plus puissant.

microsoft SQL server : payant , utilisé souvent en combinaison avec ASP.NET.
postgreSQL : similaire à MYSQL avec plus d'option ( gratuit ).

<<<<<<< HEAD
03/04/2018:

Le serveur est le seul qui puisse exécuter/lire le php ,donc ce cas on est oubliger de transformer notre ordinateur
en serveur à travers l'installtion des logiciels que le serveur utilise.

pour un site statique :

on a besoin que d'un :
1) éditeur de texte : un progrmme tel que le bloc-notes;note pade++ ( contient le code ).
2)un navigateur web : afin de tester notre page web,tel que mozilla firefox,internet explorer,google crome,dont il faut tester notre site web sur tout
les navigateurs .

Avec un site dynamique :

l'éditeur et le navigateur n'est pas suffisant dans ce cas,or on aura besoin d'autre logiciels/programmes  pour que l'ordinateur puisse se comporter comme un serveur pour lire le php 
 tel que:

Apache :c'est un serveur web qui est charger de délivrer les pages web aux visiteur, il ne gére que le HTML, dans ce cas il faut lui compléter avec d'autr programme tel que le php.


php:c'est un plug-in pour Apache,qu'il lui permet de traiter des pages web dynamique en php.

MYSQL:c'un logociel de géstion de base de données, permet d'enregistrer des données de maniére organisé.


=======
###########################################  
	
	la tu as fait du bon travail. du coup je te demande de lire jusque à la page 33 , pour avoir une idée sur l'envirenement de travail
	
	j'aimerai bien si tu peut terminer cette partie demain .
	
	bonne courage. :*
	
###########################################
>>>>>>> 6a80aeab929d3cf3fdfd3857d4f7f7997e33a0ed


04/04/2018:

ii ya plusiére programmes ayant les packs qui contient ( le serveur Apache ,php et MYSQL) chacun est compatible à un systéme 
d'exploitation déterminé.
sous windows :on utilise le programme wamp 
sous mac os x: on utilise le programme mamp 


sous linux = on utilise le programme xampp

root : et le compte administrateur de la machine qui a notamment le droit
 d'installer les programmes.


il exixte des éditeurs convenable pour chaque systéme d 'éxploitation :

sous windows : on recommande notepad++ ( gratuit ).


sous mac os x : on recommande textwrangler .

sous linux : éditeur graphique / GEDIT.
             éditeur avec console : vim emacs.



######################################

cette partie touche à sa fin , il a permet de decouvrir l'envirenemont de php. 
l'etape suivante est de decouvrir comment ecrie notre premier code en php , l'execute et voir le resultat.

   
######################################
 




