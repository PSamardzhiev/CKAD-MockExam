# Mock Exam 1 Challenges

## 1: Deploy a pod named nginx-448839 using the nginx:alpine image.

## 2: Create a namespace named apx-z993845

## 3: Create a new Deployment named httpd-frontend with 3 replicas using image httpd:2.4-alpine

## 4: Deploy a messaging pod using the redis:alpine image with the labels set to tier=msg

## 5: A replicaset ***rs-d33393*** is created. However the pods are not coming up. Identify and fix the issue

## 6: Create a service ***messaging-service*** to expose the ***redis*** deployment in the marketing namespace within the cluster on ***port 6379***

## 7: Update the environment variable on the pod webapp-color to use a green background

## 8: Create a new ConfigMap named cm-3392845. Use the spec given on the below

```bash

ConfigName Name: cm-3392845

Data: DB_NAME=SQL3322

Data: DB_HOST=sql322.mycompany.com

Data: DB_PORT=3306
```

## 9: Create a new Secret named db-secret-xxdf with the data given (on the below)

```bash
Secret Name: db-secret-xxdf

Secret 1: DB_Host=sql01

Secret 2: DB_User=root

Secret 3: DB_Password=password123
```

## 10: Update pod app-sec-kff3345 to run as Root user and with the SYS_TIME capability.

## 11: Export the logs of the e-com-1123 pod to the file /opt/outputs/e-com-1123.logs
It is in a different namespace. Identify the namespace first

## 12: Create a Persistent Volume with the given specification.

```bash
Volume Name: pv-analytics

Storage: 100Mi

Access modes: ReadWriteMany

Host Path: /pv/data-analytics
```

## 13: Create a redis deployment using the image redis:alpine with 1 replica and label app=redis. Expose it via a ClusterIP service called redis on port 6379. Create a new Ingress Type NetworkPolicy called redis-access which allows only the pods with label access=redis to access the deployment

## 14: Create a Pod called sega with two containers:

```bash
Container 1: Name tails with image busybox and command: sleep 3600.
Container 2: Name sonic with image nginx and Environment variable: NGINX_PORT with the value 8080.
```




