16/01/2021 08:36
# Meeting
- [ ] 10H : restore et distribution tâches

# Step 0 : inventory
- [ ] il y a encore des crons qui tourne ? (voir les erreurs mails) merci de les identifier pour next time : **?**

# Step 1 : system up
- [ ] restore db
- - [ ] restore : Alexis
- - [ ] replication cluster : Alexis
- - [ ] check data : **?**
- [ ] restart PP
- - [ ] restart & check Charleroi : **?** 
- - [ ] restart & check Rochefort : **?** 
- - [ ] restart & check wixhou : **?**  
- - [ ] restart & check Nivelles : **?** 
- - [ ] restart & check La Louviere : **?** 
- - [ ] restart & check Grimbergen : **?** 
- - [ ] restart & check Maraidsous : **?** 
- - [ ] restart & check Madeira : **?** 
- - [ ] restart & check ppX : **?** 
- [ ] restart PrintPack : Julien J
- [ ] restart Mailid : Julien J
- [ ] restart webhook chez Mailjet : **?**
- [ ] restart Cron Linux
- [ ] check Observium
- [ ] check logs error

# Step 2 : check old job
- [ ] DB : éffacer/mettre en test les jobs toujours temp du **14**/1 : **?**
- [ ] PrintPack : éffacer/renommer les jobs toujours ouvert du 15/1 : Julien J

# Step 3 : SFTP/LPR
- [ ] restart SFTP/LPR
- - [ ] restart SFTP : **?**
- - [ ] restart LPR : **?**
- - [ ] check File/ftp checker : **?** 
- - [ ] activation alertes et autres SMS : **?**

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

* * *
# lundi : analyse de l'incident
