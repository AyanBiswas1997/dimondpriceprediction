## this is the tep of end to end project 
#  this is the steps.......
git init.........

git add abc.txt

git add .

git commit -m "this is my first commit"

git pull


bash your_file_name.sh


python setup.py install

for login in dagshub you will follow this 



import dagshub
dagshub.init(repo_owner='AyanBiswas1997', repo_name='dimondpriceprediction', mlflow=True)

import mlflow
with mlflow.start_run():
mlflow.log_param('parameter name', 'value')
mlflow.log_metric('metric name', 1)