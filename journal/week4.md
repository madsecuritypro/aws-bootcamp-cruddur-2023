# Week 4 — Postgres and RDS


aws rds create-db-instance \
  --db-instance-identifier cruddur-db-instance \
  --db-instance-class db.t3.micro \
  --engine postgres \
  --engine-version  14.6 \
  --master-username crudderroot \
  --master-user-password MaddyDB01 \
  --allocated-storage 20 \
  --availability-zone ca-central-1a \
  --backup-retention-period 0 \
  --port 5432 \
  --no-multi-az \
  --db-name cruddur \
  --storage-type gp2 \
  --publicly-accessible \
  --storage-encrypted \
  --enable-performance-insights \
  --performance-insights-retention-period 7 \
  --no-deletion-protection

![image](https://user-images.githubusercontent.com/125198688/224503610-1efae95e-c8d5-41da-80a8-cd5cc682c1e8.png)

![image](https://user-images.githubusercontent.com/125198688/224503589-76fe3fa3-7d8f-4bea-ad55-a11299b61e13.png)

![image](https://user-images.githubusercontent.com/125198688/224503726-ec116eb2-1999-46fe-8744-a733419792b8.png)

![image](https://user-images.githubusercontent.com/125198688/224503770-42140d91-4179-4dcc-a22e-b30e6183835a.png)


![image](https://user-images.githubusercontent.com/125198688/224504286-6721d47d-6ac3-4bb8-97f9-24a9b4d46b90.png)
![image](https://user-images.githubusercontent.com/125198688/224504335-2a7f41ee-d44c-4666-8e73-7052a5e27653.png)
![image](https://user-images.githubusercontent.com/125198688/224504422-a7da02e8-1759-4cfc-97f8-2fe763d80aab.png)


![image](https://user-images.githubusercontent.com/125198688/224504573-5400ef93-4ea4-46fd-a688-e12f40f6c6b4.png)


export CONNECTION_URL="postgresql://postgres:password@localhost:5432/crudder"


![image](https://user-images.githubusercontent.com/125198688/224505582-cde558c1-62c7-4e4d-a427-d35c274a0ca1.png)
![image](https://user-images.githubusercontent.com/125198688/224505632-2880928c-4a87-4910-8bfa-ad8bf1f29629.png)


![image](https://user-images.githubusercontent.com/125198688/224506021-b122b410-f325-405f-9414-776ab3209e6b.png)

![image](https://user-images.githubusercontent.com/125198688/224506525-2f51df5c-78e2-4235-a67a-5a85a81a0647.png)



![image](https://user-images.githubusercontent.com/125198688/224503726-ec116eb2-1999-46fe-8744-a733419792b8.png)


![image](https://user-images.githubusercontent.com/125198688/224510090-5408c088-7f16-417f-a11c-b1ecca905b92.png)
