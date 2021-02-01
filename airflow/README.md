# Deploy Airflow on a Linux web app with PostgreSQL

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Feavanvalkenburg%2Farm-templates%2Fmaster%2Fairflow%2Fazuredeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/ alt="Deploy to Azure">
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Feavanvalkenburg%2Farm-templates%2Fmaster%2Fairflow%2Fazuredeploy.json" target="_blank">
  <img src="http://armviz.io/visualizebutton.png"/>
</a> 

This template provides a easy way to deploy a puckel/docker-airflow docker image on a Linux Web App with Azure database for PostgreSQL and Azure Redis for Celery.

**Note** Once deployed Airflow can take a while to start due the creation and initialization of Airflow database.
