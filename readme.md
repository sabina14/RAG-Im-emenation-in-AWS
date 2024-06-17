RAG APPLICATION USING AWS SERVICES USING 
aws lambda,aws ecr, langchain, hugging face, docker, aws bedrock

1.create env using conda create -p env python=3.10 -y

2.source activate ./env

3.create requirements file and install all dependencies

4.create setup.py file and include any local packages required

5. create .gitignore file and add .env

6. create .env file and add api keys required
7. install (git bash from google )and start git init
8. create DockerFile
9. create repo in github and git add .
10. git commit -m 'code folder upgrade'
11. git remote add origin --repo linkclear
12. git status
13. git remote -v
14. git push -u origin main
15. pip install awscli
16.create user in iam and attach policy give admin acess genererate key
17.create qa system folder and create app.py
18.create main.py and import libabries
19. create test.json and write payload details that main.py requires
20. at terminal aws configure-give access key and secret key,give region --useast1,type:json
21.python main.py##donnects to api gets the output
22.try stable diffusion 

https://github.com/sabina14/RAG-Implemenation-in-AWS.git

day3:

write app.py imports

write ingestion code - data pdf n data folder, install faiss-cpu, python ingestion.py

code retrieval and generation.py, give setup.py for qasystem module aceess and give python setuup.py install

write remaining code in app.py

day4:
create DockerFile and dockerignore files and add '-e.' in requirements 
write commands tin dockerfile to create image and push to ecr
create folder github and main.yaml for the github actions to update in github /ecr automatic. 
and create a workflow folder inside github and move main.yaml inside worlfow and write the commands

in aws.secrets guve all secret key access in 4 areas

git remote -v ---gives link 

after pushing these changes github actions has the workflow that has something running
add dockerignore files

push to git---workflow should get updated

in jobs ci cd shoutld get updated and docker image created in aws ecr 













 