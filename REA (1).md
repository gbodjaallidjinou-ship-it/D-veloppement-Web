<div align = "center">
<img src="image/logo.png align="lefter"width="120/>
<img src="image/drapeau.png align="right"with="120"/>
<br> <br> <br>
#** REPUBLIQUE DU BENIN **
#** Ministere de l'enseignement secondaire et de la recherche scientifique**
<br> <br>
###** Niveau d'etude:Licence1 **
###** Discipline: Fondamentaux des reseux et systemes **
<br> <br>
<div style="border:2px solid black;padding:10px;display";>

##**THEME**
###**L'ADRESSAGE IP ET LES DIFFERENTS PROTOCOLES RESEAUX**

   </div>
   <br> <br> <br>
   ###** Professeur:Mr KEKE Turnibio**
 <br> <br>
 ###**Réalisé par : **
 ###**[ALLIDJINOU Cédric]
 <br> <br> <br> <br>
 ###** Annéé Académique:2025-
 </div>

 ### PLAN

###  Introduction
   </div>
 
   

###  I. L’adressage IP
1. Définition  
2. Les types d’adresses IP  
3. Les classes d’adresses IP  
4. Adresse IP publique et privée  

###  II. Les protocoles réseaux
1. Définition  
2. Les principaux protocoles  
3. Le modèle TCP/IP  

###  III. Relation entre adressage IP et protocoles

### Conclusion

###  Bibliographie

## Introduction

Un réseau informatique est un ensemble d’ordinateurs et d’appareils connectés entre eux afin d’échanger des informations. Ces appareils peuvent être des ordinateurs, des téléphones, des serveurs ou encore des objets connectés.

Aujourd’hui, les réseaux sont indispensables dans notre quotidien. Ils permettent la communication entre machines, que ce soit pour naviguer sur Internet, envoyer des emails, regarder des vidéos ou utiliser des applications.

Pour que ces échanges soient possibles, deux éléments sont essentiels :

- L’adressage IP, qui permet d’identifier chaque appareil  
- Les protocoles réseaux, qui définissent les règles de communication  

Dans cet exposé, nous allons étudier ces deux notions fondamentales et leur relation.

##  I. L’adressage IP

### 1. Définition

Une adresse IP (Internet Protocol) est un identifiant unique attribué à chaque appareil connecté à un réseau.

**Rôle :**
- Identifier chaque machine  
- Permettre l’envoi et la réception de données  

On peut comparer une adresse IP à une adresse postale : elle permet de savoir où envoyer les informations.

### 2. Les types d’adresses IP

####  IPv4

- Format : 4 nombres séparés par des points  
- Exemple : `192.168.1.1`  
- Chaque nombre est compris entre 0 et 255  
- Limite : environ 4 milliards d’adresses  

#### IPv6

- Format plus long, en hexadécimal  
- Exemple : `2001 :0db8 :85a3 :0000 :0000 :8a2e :0370 :7334`  
- Avantage : nombre d’adresses quasi illimité  
- Conçu pour remplacer IPv4  

### 3. Les classes d’adresses IP

Les adresses IPv4 sont divisées en classes :

#### Classe A
- Grandes organisations  
- Exemple : `10.0.0.0`  
- Beaucoup d’hôtes possibles  

#### Classe B
- Organisations moyennes  
- Exemple : `172.16.0.0`  

#### Classe C
- Petits réseaux  
- Exemple : `192.168.1.0`  

 Aujourd’hui, ce système est remplacé par le CIDR, mais reste utile pour comprendre les bases.

### 4. Adresse IP publique et privée

####  IP publique
- Visible sur Internet  
- Unique dans le monde  
- Fournie par un fournisseur d’accès Internet  

#### IP privée
- Utilisée dans un réseau local  
- Non accessible directement depuis Internet  

**Exemples :**
- `192.168.x.x`  
- `10.x.x.x`  

 Un routeur permet de relier IP privée et IP publique.

## II. Les protocoles réseaux

### 1. Définition

Un protocole réseau est un ensemble de règles qui permettent aux appareils de communiquer entre eux.

** Il définit :**
- Comment les données sont envoyées  
- Comment elles sont reçues  
- Comment elles sont interprétées  

### 2. Les principaux protocoles

####  http / HTTPS
- Utilisés pour naviguer sur le web  
- HTTPS est sécurisé (chiffrement)

#### FTP
-	Transfert de fichiers entre ordinateurs  

#### SMTP
-	Envoi des emails  

####  POP / IMAP
- POP : télécharge les emails  
- IMAP : synchronise avec le serveur  

####  DNS
- Traduit les noms de domaine en adresses IP  
- Exemple : `google.com` → adresse IP  

### 3. Le modèle TCP/IP

Le modèle TCP/IP comporte 4 couches :

#### Couche Application
- Interaction avec l’utilisateur  
- Protocoles : http, FTP, SMTP  

#### Couche Transport
- Transmission des données  
- TCP : fiable  
- UDP : rapide  

#### Couche Internet
-	Gère l’adressage IP et le routage  

#### Couche Accès réseau
-	Transmission physique (Wi-Fi, câbles)


## III. Relation entre adressage IP et protocoles

L’adressage IP et les protocoles réseaux sont complémentaires :

- L’adresse IP identifie les machines  
- Les protocoles organisent la communication  

###  Exemple : navigation sur Internet

1. L’utilisateur entre une adresse web  
2. Le DNS trouve l’adresse IP  
3. Le navigateur envoie une requête http  
4. Le serveur répond avec la page  

**Sans adresse IP → impossible de localiser**  
**Sans protocole → impossible de communiquer**


##  Conclusion

L’adressage IP et les protocoles réseaux sont deux éléments fondamentaux du fonctionnement des réseaux informatiques.

- L’adresse IP permet d’identifier chaque machine  
- Les protocoles définissent les règles de communication  

Grâce à ces mécanismes, les échanges de données sont rapides et fiables à l’échelle mondiale.

Sans eux, Internet tel que nous le connaissons n’existerait pas.

###  Ouverture

Les réseaux évoluent avec :
- IPv6  
- La 5G  
- L’Internet des objets (IoT)  

Ces innovations permettront de connecter encore plus d’appareils dans le futur.


##  Bibliographie

1. TANENBAUM, Andrew S. – *Réseaux informatiques*, Pearson  
2. KUROSE, James F. & ROSS, Keith W. – *Computer Networking : A Top-Down Approach*, Pearson  
3. STALLINGS, William – *Data and Computer Communications*, Pearson  


