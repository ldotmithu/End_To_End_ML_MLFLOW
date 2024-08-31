# End_To_End_ML_MLFLOW

git config --global user.email "ldotmithurshan222@gmail.com"
git config --global user.name "ldotmithu"


import dagshub
dagshub.init(repo_owner='ldotmithu', repo_name='End_To_End_ML_MLFLOW', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


  https://dagshub.com/ldotmithu/End_To_End_ML_MLFLOW.mlflow

  ec98f4a9bd5ed641197839391e079d81a56e4f9a


export MLFLOW_TRACKING_URI=https://dagshub.com/ldotmithu/End_To_End_ML_MLFLOW.mlflow

export MLFLOW_TRACKING_USERNAME=ldotmithu 

export MLFLOW_TRACKING_PASSWORD=ec98f4a9bd5ed641197839391e079d81a56e4f9a

