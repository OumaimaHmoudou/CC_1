# Partie 1 
#  1-   il manque le datastream  donc on va créer un fichier  datastream ( kisesis_datastream.tf)  et  un fichier de destination S3 bucket : destination_s3_bucket.tf
#  5- user_data un outil utile pour se débarrasser des opérations de routine après le provisionnement du serveur.
#  6- le role de l'agent Kineis sur la VM EC 2 qui permet de collecter et d'envoyer facilement des données à Kinesis Data Streams
#Partie 2 
#l'architecture de données de ce data pipeline 
# 1- ingestion : la récupération /importation des données depuis différentes sources, dans un système de traitement où elles seront stockées, transformées, analysées et exposées
# Outils utilisé est AWS Kinesis data Streams  sont but et de réceptionner le flux de données  
# 2- Stockage : Amazon S3 bucket permet de stocker sous form d'objet 
# 3- transformation : amazon Kinesis data  analytics  permet de faire  traitement des données par une application
# 4- exposition : Amazon Cloud Front il permet de diffuser le contenu final 