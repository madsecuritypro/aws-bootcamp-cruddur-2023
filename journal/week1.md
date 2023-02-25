# Week 1 — App Containerization


### Routine Billing Checkup

- [x] Gitpod



![image](https://user-images.githubusercontent.com/125198688/221349910-977c02df-cff6-4940-b262-0eb37a3b31f0.png)


- [x] AWS
* To remain under free tear Chirag's recommendation was to avoid Cloud Trail for this bootcamp or be very cautious and use settings to only log mamagement events. Also AVOID logging KMS Encryption.
******************************************************************

<br/>
<br/>

## CTO expectation is to containerize the application
1. React JS = Frontend
2. Python Flask = Backend

<br/>
<br/>

## Containerize Backend

### Run Python
```sh
cd backend-flask
export FRONTEND_URL="*"
export BACKEND_URL="*"
python3 -m flask run --host=0.0.0.0 --port=4567
cd ..
```

- make sure to unlock the port on the port tab
- open the link for 4567 in your browser
- append to the url to `/api/activities/home`
- you should get back json


![image](https://user-images.githubusercontent.com/125198688/219881172-c4cd3341-258e-4eba-a545-cc622963c932.png)

### Build Container

```sh
docker build -t  backend-flask ./backend-flask
```


![image](https://user-images.githubusercontent.com/125198688/219881638-75f2a70b-c36a-43c1-896e-61bdbd7dc21d.png)
<br/>
<br/>

![image](https://user-images.githubusercontent.com/125198688/219881658-90f0654b-d0a4-4dd1-acce-b4ca4441b7ce.png)
<br/>
<br/>

![image](https://user-images.githubusercontent.com/125198688/219881813-61b32281-f14a-4208-bdc7-2fa50dd5d1fa.png)
<br/>
<br/>

![image](https://user-images.githubusercontent.com/125198688/221353143-578caa75-3740-425f-ad34-600b28ff613d.png)

<br/>
<br/>

## Create the notification feature

### Joining and authenticating into the crudder application first

![image](https://user-images.githubusercontent.com/125198688/221366591-76f99aaa-4284-407b-8db7-8fd4c1bbf933.png)

![image](https://user-images.githubusercontent.com/125198688/221366676-95acc1aa-ef55-4ac7-8016-13f9b9a15c06.png)

### Update the OpenAPI to add Notifications

![image](https://user-images.githubusercontent.com/125198688/221367860-cc30da5e-91e8-4d58-a61d-174ae7b718f9.png)

