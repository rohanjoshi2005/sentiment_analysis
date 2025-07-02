# sentiment_analysis


import dagshub
dagshub.init(repo_owner='rohanjoshi2005', repo_name='sentiment_analysis', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)