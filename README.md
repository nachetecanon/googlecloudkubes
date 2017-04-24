# googlecloudkubes

## creation of the cluster 
gcloud container clusters create cluster-1 --zone europe-west1-b

## creation of volume disks
gcloud compute disks create mongodb-disk1
gcloud compute disks create mongodb-disk2
gcloud compute disks create mongodb-disk3