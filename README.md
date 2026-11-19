# ReadMe
#Infrastuctor Engineer Test
Task 1 =  [https://github.com/chanachonktp7/dockerfile/issues/3](https://github.com/chanachonktp7/dockerfile/issues/3#issue-6481652322) 
Task 2 = repo docker-compose.yml[https://github.com/chanachonktp7/docker-compose.yml/blob/main/docker-compose.yml](https://github.com/chanachonktp7/docker-compose.yml/blob/main/docker-compose.yml)" 
         env. [https://github.com/chanachonktp7/env/blob/main/webapp.env](http://github.com/chanachonktp7/env/blob/main/webapp.env)"
Task 3 = Dockerfile repo "[Dockerfile](https://github.com/chanachonktp7/dockerfile)"
Task 4 = Nginx Config "[https://github.com/chanachonktp7/nginx](https://github.com/chanachonktp7/nginx/blob/main/default.conf)" 

#Directory structure
web-application/
│
├── docker-compose.yml
├── .env
│
├── nginx/
│   └── default.conf
│
├── backend/
│   ├── Dockerfile
│   ├── requirements.txt
│   └── manage.py
│
└── frontend/
    ├── Dockerfile
    ├── package.json
    └── src/
#Step 1    
1.Install Docker&Docker compose
2.Create docker-compose.yml
3.Create .env
4.Config default.conf in nginx
5.Create Blackend/Dockerfile
6.Create backend/requirements.txt
7.Create frontend/Dockerfile
#Step 2
1.docker compose build
2.docker compose up -d
3.docker compose ps #contrainer running Check
4.docker compose logs -f #View application logs
