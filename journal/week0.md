# Week 0 — Billing and Architecture

**High Level Application Requirements:**
1. Application using micro services
2. The frontend is in JS and the backend is in Python
3. Using api to communicate
4. Authentication using Cognito
5. Use as much as possible the aws free tier
6. Momento as a third party caching system


Architecture Diagrams:

[Conceptual Diagram](https://lucid.app/lucidchart/1cb377e3-1865-4021-95bf-be06b4c94a2c/edit?viewport_loc=-11%2C96%2C1957%2C976%2C0_0&invitationId=inv_79d21c87-6a7d-488a-b15d-9d8a81113f97)

![image](https://user-images.githubusercontent.com/125198688/219836446-c0e0d118-2d54-482b-9b9e-8644def2597d.png)

[Logical Diagram](https://lucid.app/lucidchart/1483e0dc-c5bb-4062-bcb0-9e2941e05b8c/edit?view_items=gmnyJJXMyBQ-&invitationId=inv_24bd6ac3-ea9b-4d8c-9465-013b0e870855)
![image](https://user-images.githubusercontent.com/125198688/219874596-186d26e0-3d0a-4021-98ae-dd4b27425fb9.png)



Create a new User and Generate AWS Credentials

![image](https://user-images.githubusercontent.com/125198688/219837003-57d125d6-feb1-4ae9-a3c5-3a7b034e5ef8.png)


#Launching AWS CloudShell and looking at AWS CLI

AWS CloudShell (Adding an auto prompt)

<img width="1512" alt="Screenshot 2023-02-17 at 3 17 38 PM" src="https://user-images.githubusercontent.com/125198688/219795503-e48fd068-7b48-4da2-9755-a73903dff446.png">


<img width="1267" alt="image" src="https://user-images.githubusercontent.com/125198688/219796210-adebbcce-fd4a-4f56-a2bb-00fa520ab995.png">



Installed AWS CLI
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/125198688/219829593-f9a591f7-d886-4cd0-86bf-a547d243f6a3.png">

Set Env Vars

We will set these credentials for the current bash terminal
![image](https://user-images.githubusercontent.com/125198688/219830211-809aa269-2928-426c-87b6-99c41826d39e.png)


Installed AWS CLI via Gitpod

<img width="1512" alt="image" src="https://user-images.githubusercontent.com/125198688/219829593-f9a591f7-d886-4cd0-86bf-a547d243f6a3.png">

![image](https://user-images.githubusercontent.com/125198688/219843847-fe9e1dc1-bbcb-4cf6-8f21-edbd04418554.png)



Created Budget via AWS CLI 

![image](https://user-images.githubusercontent.com/125198688/219844786-b3060423-45e4-4734-848b-fb0b1444fa7c.png)

![image](https://user-images.githubusercontent.com/125198688/219844737-9238094e-218b-4df3-9c3a-47e85f5e26ca.png)


Created Budget via AWS Console
![image](https://user-images.githubusercontent.com/125198688/219868916-d5f263e1-e29e-437c-acfb-903f443aec12.png)


SNS - Simple Notification Service - ALARM

![image](https://user-images.githubusercontent.com/125198688/219845890-8b7dbc9d-bd3d-498b-b788-f3fc83c6aaa1.png)

<img width="1489" alt="image" src="https://user-images.githubusercontent.com/125198688/219846027-4a914daa-c7da-4d8f-bae1-805ef2ea5376.png">



<img width="1489" alt="image" src="https://user-images.githubusercontent.com/125198688/219846059-3a10d585-50a2-4291-9956-b193737486e7.png">

![image](https://user-images.githubusercontent.com/125198688/219846099-867ebf90-976a-423b-acbd-6dcc5508669f.png)



![image](https://user-images.githubusercontent.com/125198688/219847059-e641c53f-2de2-45ae-9dbf-a3131044ab41.png)

