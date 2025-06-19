# GCP VPC Peering

## Create VPC in asia-southeast1 region

https://console.cloud.google.com/networking/networks/details/fernando-vpc-1?project=fernandokarnagi&authuser=2&inv=1&invt=Ab0hCg&pageTab=OVERVIEW

![image](https://github.com/user-attachments/assets/b42bce31-5967-4e35-a9c2-2cda6f765dcd)

## Create VM in asia-southeast1 within this VPC

https://console.cloud.google.com/compute/instancesDetail/zones/asia-southeast1-b/instances/fernando-mongodb-ce-1?authuser=2&inv=1&invt=Ab0fgg&project=fernandokarnagi

![image](https://github.com/user-attachments/assets/bb83fd39-2196-4f81-80b4-92558945a6c5)
![image](https://github.com/user-attachments/assets/299419aa-fcba-49bf-be5b-9239fd073cf5)

## Create Peering Connection

![image](https://github.com/user-attachments/assets/100001e8-e91b-485f-9af5-b8e0925487c5)

Populate project ID and VPC Name

![image](https://github.com/user-attachments/assets/ff4d3997-5d91-4b4b-91c8-19b6dc93f421)

Once initiated, peering request is created as shown below

![image](https://github.com/user-attachments/assets/63d7ee78-a17b-47e4-8751-ed2b695de90b)

Now, create a reciprocal connection from GCP to Atlas to complete this connection

![image](https://github.com/user-attachments/assets/831a33b2-62dc-4923-a3ae-b45b429f370e)

VPC Peering is created in GCP and Atlas

![image](https://github.com/user-attachments/assets/71f81b62-85f1-4ab6-8742-fdda01901547)

![image](https://github.com/user-attachments/assets/b75583fc-5acd-4c9d-a84f-836637fa67e9)

## Test connectivity

From fernando-mongodb-ce-1 VM

![image](https://github.com/user-attachments/assets/714b4309-b745-4e3b-96d3-d4eea60f557b)



