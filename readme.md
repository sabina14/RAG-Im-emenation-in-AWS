RAG APPLICATION USING AWS SERVICES USING 
aws lambda,aws ecr, langchain, hugging face, docker, aws bedrock
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
21.python main.py##donnects to api gets the output(renamed as llama2.py)
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

day5:
activate env

run app.py

deploy image cretaed  in ecr--got to aws app runner--create service--container registry--
ecr--give url --continue--deployment seting--automatic--create new service role\--next--service name:ragdeployment--4cpu--12gb--port no :8080..-createnew service role=--next deploy--check url for working


amazon sagemaker--create domain--single user setup--(using meat llama2)(search hugging afce on aws sagemaker for deatil documentation)

doaminname--login through iam--create new role----create bucket in s3 and add that bucket--next--sagemaker new--next--vpc--default----sg--next--submit--once domain craeted-got otuser-launch--sagemakerstudio--





day6 & 7:

goto amazon sagemaker. get started--sagemaker studio-open/ juytrt instance--python kernel--connect to cluster--code in llamasagemakercode.iypnb


(sagemaker requires--iam,s3..hugging face/llama2/gemini)
(search hugging afce on aws sagemaker for deatil documentation)

jupyter lab space--configure the instance launch jupyrt lab and write the code


below json modelid--llama2 hugging face model id
instance type mlm5.2x large


once deployed-goto homepage --deployment--you will get the end point











 