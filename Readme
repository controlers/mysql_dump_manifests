Using Kubernetes CronJob to Backup MySQL on GKE

Step1:
Create IAM Service Account In GoogleCloud

Step2:
Create the Service Account In GKE

Step3:
Create a Kubernetes Secret In GKE

Step4:
Creating a storage bucket

Step5:
Backup script
use file name is buckup_secript.sh

Step6:
MySQL Backup Docker Image DockerFile
Use file name is Dockerfile 
Build Command As follows
docker build -t gcr.io/serverlab/mysql-backup:0.0.1 .
docker push gcr.io/serverlab/mysql-backup:0.0.1

Step7:
Create A Kuberbetes CronJob
Use file name is Mysql_dump_cronjob.yaml

