# ReadMe
Directory structure
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
1.Install Docker&Docker compose
2.Create docker-compose.yml
3.Create .env
4.Config default.conf in nginx
5.Create Blackend/Dockerfile
6.Create backend/requirements.txt
7.Create frontend/Dockerfile

Step
1.docker compose build
2.docker compose up -d
3.docker compose ps #contrainer running Check
4.docker compose logs -f #View application logs
