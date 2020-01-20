# Template for new serverless backend

Helps to start new serverless backend with:
- python 3.8
- serverless framework
- aws

Steps:
- Clone project
```
git clone git@github.com:andr81/sls-aws-python-template.git
```
- serverless.yml: change project, service, region, aws-account-id
- Install npm, serverless, docker, python
- Install python virtual environment
```
virtualenv venv --python=python3
```
- Install sls plugins
```
sls plugin install -n serverless-python-requirements
```
- Deploy
```
sls deploy
```
- Test
```
curl https://yoururl.execute-api.us-east-1.amazonaws.com/prod/ping
```
- Delete .git folder
- Ready