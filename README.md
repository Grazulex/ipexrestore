16/01/2021 08:36

**vous ne faites rien sans mon accord please. on doit etre synchro**

# Meeting
- [X] 10H : restore et distribution tâches
- [X] 15H : final check system up/running
- [X] 16h30 : check import from elastic
- [X] 18h30 : restart FTP/LPR
- [X] 19h : confirmation Partena/Ores
- [X] 9h30 : confirmaton insertion files/documents & extra
- [X] 10h15 : Go prod
- [X] 10h45 : check clients
- [X] 18h30 : check prod

# contact
- [ ] si problème printpack / mailid : contactez JJ please

# Step 0 : inventory
- [ ] il y a encore des crons qui tourne ? (voir les erreurs mails) merci de les identifier pour next time : **jimmy**

# Step 1 : system up
- [X] restore db
- - [X] restore : Alexis
- - [X] replication cluster : Alexis
- - [X] check data : **Isma**
- [X] restart PP
- - [X] restart ohain : **zak**
- - [X] restart & check Charleroi : **ALL** 
- - [X] restart & check Rochefort : **ALL** 
- - [X] restart & check wixhou : **ALL**  
- - [X] restart & check Nivelles : **ALL** 
- - [X] restart & check Corse : **ALL** 
- - [X] restart & check Namur2 : **ALL** 
- - [X] restart & check La Louviere : **ALL** 
- - [X] restart & check Madeira : **ALL** 
- - [X] restart & check Herstal : **ALL** 
- [X] restart PrintPack : Julien J
- [X] restart Mailid : Julien J
- [X] check Observium : 
- - [X] api : **isma**
- - [X] infra : **zak**
- [X] check logs error

# Step 2 : check old job OR import from elastic
- ~~[ ] DB.a : éffacer/mettre en test les jobs toujours temp du **14**/1 : **isma/jimmy**~~
- [X] DB.b : importer depuis elastic : **isma/jimmy**
- ~~[ ] PrintPack : éffacer/renommer les jobs toujours ouvert du 15/1 : Julien J~~--

# Step 2b si DB.b : last start AFTER import data
- [X] restart all PP services : **ALL**
- [X] restart webhook chez Mailjet APRES IMPORTATION : **isma**
- [X] restart Cron Linux APRES IMPORTATION : **Jimmy**

# Step 3 : SFTP/LPR
- [X] restart SFTP/LPR
- - [X] restart SFTP : **zak**
- - [X] restart LPR : **zak**
- - [X] check File/ftp checker : **Pierre G** 
- - [X] activation alertes et autres SMS : **zak**

# Step 4 : communication system up
- [X] communication vers sales que le systeme est up/running (plus de data DB du 14/01 18h à ce jour). : **?**

les fichiers SFTP/LPR du 14/01 18h jusqu'à ce jour sont encore là mais plus en DB. 
1. soit le client les reupload
2. soit on doit les insérer manuellement. 

Preference pour solution 1

# step 5 : wait feedback Sales/Customers
- [ ] customer upload himself his files
-  - [ ] if yes : check system
-  - [ ] if no : insert again all files in DB via file/ftpchecker  

# step 6 : prodution
## Partena 300
- [ ] clean folder in : **?**
- [ ] check job/file stil open : **?**
- [ ] send file from vip : **?**
- [ ] check if system running : **?**
- [ ] call to Oliver and Raymond to give GO : **?**
- [ ] reporting à revoire : lundi **Julien V**
- [ ] Prod 300 **Julien V**

## Partena 740
- [X] : Produit mais pas en DB -sur Robert-
- - 1003 pas d'extra : expedier vendredi
- - 1004 pas en DB : rapport pour lundi.
- - [ ] : Rapport pour Lundi matin.

## Partena CAF
- [ ] : pour Dimanche après-midi.**Pierre** - a valider.

## Ethias
- [X] voir avec Julien V : **jms** : tout ok sauf rapport pour lundi

## Somedi
- [X] gros job en cours : validation **Jimmy** 
- - job a tourné la nuit de jeudi à vendredi.

## Fednot
- [ ] va renvoyer des fichier
- - [ ] contacter sales/client : Sebastien Canivet
- - - [ ] Lidwin Do Hu : Lidwine.Do.Huu@fednot.be
- - [ ] check system : **?**
- - [ ]le dernier a tourné avant la coupure, le prochain sera ce soir
- - [ ] Integrité du job a valider : **Baptiste** 
- - [ ] ( jeudi ) Feedback : manque reference mailID - erreur humaine- à valider. **Ludo** / **Baptiste**
- - [ ] job du vendredi : moins de document que ce qu'il y a dans l'API : **Ludo** / **Baptiste**
- - [ ] job de ce soir : OK.

## Ores
- [X] va renvoyer des fichier
- - [X] contacter sales/client : Sebastien Canivet
- - - [ ] farid.elbrahmi@ores.be
- - - [ ] KEVIN.MARISCHAL@ORES.BE
- - [ ] check system  : **?**
- - [ ] pas de fichier sur le FTP : à checker avec Ores.

## Clients ayant tournés le weekend dernier :
- [X] UCM : produit OK
- [X] KidsLife : job a lancer. ( normalement vendredi 21.00h )
- [ ] Verisure : le dernier a tourné avant la coupure, le prochain sera lundi
- - [X] integrité à verifier **Baptiste**
- - [ ] rapport pour Lundi **Baptiste**
- [X] Luris : pas d'impact **Julien J**
- [X] Mega : rien
- [X] EuropA : **Julien J**
- - Dernier Job : vendredi matin **Julien J**
- [ ] MultiSend : refaire Job extra pour lundi 3.00h : pas d'impact **?**
- - [X] Vandessel : lancement manuel -job commplet- **Isma**
- - [ ] DocDrop : 100 fichiers - à étudier -  lundi matin **olivier**
- - [ ] mail Olivier : bloquer le depot du Multisend **Sébastien**
- [X] FamiWal : pas de job le week-end, le prochain sera Lundi à 5h du matin
- [X] Facq :  le client a envoyé un zip avec juste un fichier baseware que j'ai renvoyé à Ludo. Du coup le job qui a continué n'avait pas lieu d'être car pas de fichier. Je vais regarder pour mettre un blocage pour lorsque ce sera à nouveau le cas, mais il n'y a pas de job à relancer pour ce client 
- [X] Citadelle : a valider **Jimmy**
- [X] Ethias FullColor : Reporting Lundi **Julien V**
- [X] Ethias : No impact
- - [ ]Reporting 498 lundi **Julien V**
- [X] Resa : Job Lundi 2.00h**Julien V**
- - [ ] Valider que l'on a bien reçu tous les fichiers. A faire Lundi.
- [X] Single Deposit :**Jimmy**
- - [X] AIV : Valider 
- [ ] Partena 2020 : demander au client un réenvoie.
* * *
status Mail entre 14-01 18.00h et 15-01 18.30h : perte des status (sauf via mailjet) -uniquement preuve d'envoie idem pour A.M.
* * * 
# lundi : analyse de l'incident
