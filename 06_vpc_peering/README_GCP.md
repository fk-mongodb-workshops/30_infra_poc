# AWS VPC Peering

## Create VPC in JKT Region

https://ap-southeast-3.console.aws.amazon.com/vpcconsole/home?region=ap-southeast-3#VpcDetails:VpcId=vpc-03015093a10a213d9

![image](./img/441535483-a62423e0-cc2d-490b-a3c8-db082c9122ba.png)

## Create Atlas Network Peering

https://cloud.mongodb.com/v2/67a960a798cb747a519a8acb#/security/network/peering

![image](./img/441535590-820628ea-94f2-45da-b7b8-4a5d9f1e3e35.png)

## Approve Peering Connections

https://ap-southeast-3.console.aws.amazon.com/vpcconsole/home?region=ap-southeast-3#PeeringConnectionDetails:VpcPeeringConnectionId=pcx-026f3d0afd12ce91c

![image](./img/441535718-ea676c66-6d5b-4a17-9815-7642d8375353.png)

## Update Route Table

https://ap-southeast-3.console.aws.amazon.com/vpcconsole/home?region=ap-southeast-3#RouteTableDetails:RouteTableId=rtb-0ce1288e505b990bb

Add new routing

![image](./img/441535879-eb6bd744-0380-423f-bb20-bb13b089e041.png)

## Allow 10.0.0.0/16 into the Atlas Project Network Access

https://cloud.mongodb.com/v2/67a960a798cb747a519a8acb#/security/network/accessList

![image](./img/441536097-f6c4da95-dd47-4d2e-8b10-49da00a439c1.png)

## Test VPC from EC2

https://ap-southeast-3.console.aws.amazon.com/ec2/home?region=ap-southeast-3#InstanceDetails:instanceId=i-01a8bad4ac51199de

![image](./img/441536230-5722d953-e3cb-4a7e-9dea-06664ff8f26e.png)

Connect using MongoSH

![image](./img/441536332-5f99b6fd-e0eb-48b1-b9d3-e26008c62e25.png)


