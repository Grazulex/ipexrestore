16/01/2021 08:36

**vous ne faites rien sans mon accord please. on doit etre synchro**

# Meeting
- [X] 10H : restore et distribution tâches
- [X] 15H : final check system up/running
- [ ] 16h30 : check import from elastic

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
- [ ] check Observium : 
- - [ ] api : **isma**
- - [X] infra : **zak**
- [ ] check logs error

# Step 2 : check old job OR import from elastic
- [ ] DB.a : éffacer/mettre en test les jobs toujours temp du **14**/1 : **isma/jimmy**
- [ ] DB.b : importer depuis elastic : **isma/jimmy**
- [X] PrintPack : éffacer/renommer les jobs toujours ouvert du 15/1 : Julien J--

# Step 2b si DB.b : last start AFTER import data
- [ ] restart & check Grimbergen APRES IMPORTATION : **ALL** 
- [ ] restart & check Maraidsous APRES IMPORTATION : **ALL** 
- [ ] restart webhook chez Mailjet APRES IMPORTATION : **isma**
- [ ] restart Cron Linux APRES IMPORTATION : **Jimmy**

# Step 3 : SFTP/LPR
- [ ] restart SFTP/LPR
- - [ ] restart SFTP : **zak**
- - [ ] restart LPR : **zak**
- - [ ] check File/ftp checker : **Pierre G** 
- - [ ] activation alertes et autres SMS : **zak**

# Step 4 : communication system up
- [ ] communication vers sales que le systeme est up/running (plus de data DB du 14/01 18h à ce jour). : **?**

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

## Partena 740
- [ ] : **?**

## Partena CAF
- [ ] : **?**

## Ethias
- [ ] voir avec Julien V : **jms**

## Somedi
- [ ] gros job en cours : **Jimmy**

## Fednot
- [ ] va renvoyer des fichier
- - [ ] contacter sales/client : Sebastien Canivet
- - - [ ] Lidwin Do Hu : Lidwine.Do.Huu@fednot.be
- - [ ] check system : **?**

## Ores
- [ ] va renvoyer des fichier
- - [ ] contacter sales/client : Sebastien Canivet
- - - [ ] farid.elbrahmi@ores.be
- - - [ ] KEVIN.MARISCHAL@ORES.BE
- - [ ] check system  : **?**

## Clients ayant tournés le weekend dernier :
- [ ] UCM : **?**
- [ ] KidsLife : **?**
- [ ] Verisure : **?**
- [ ] Luris : **?**
- [ ] Mega : **?**
- [ ] EuropA : **?**
- [ ] MultiSend : **?**
- [ ] FamiWal : **?**
- [ ] Multisend : **?**
* * *
# lundi : analyse de l'incident
