# Deploy a Python (Flask) web app to Azure App Service - Sample Application


1. Realize o clone do projeto

```bash
git clone https://github.com/profjoaomenk/msdocs-python-flask-webapp-quickstart-main
```

2. Entre no diretório do projeto

```bash
cd msdocs-python-flask-webapp-quickstart-main
```


3. Realize o Deploy (Altere para seu RM entes de executar)

```bash
az webapp up \
  --resource-group rg-python \
  --location brazilsouth \
  --plan planPython \
  --name python-hello-rm9999 \
  --runtime PYTHON:3.14 \
  --sku F1
```


This is the sample Flask application for the Azure Quickstart [Deploy a Python (Django or Flask) web app to Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/quickstart-python). For instructions on how to create the Azure resources and deploy the application to Azure, refer to the Quickstart article.

Sample applications are available for the other frameworks here:

* Django [https://github.com/Azure-Samples/msdocs-python-django-webapp-quickstart](https://github.com/Azure-Samples/msdocs-python-django-webapp-quickstart)
* FastAPI [https://github.com/Azure-Samples/msdocs-python-fastapi-webapp-quickstart](https://github.com/Azure-Samples/msdocs-python-fastapi-webapp-quickstart)

If you need an Azure account, you can [create one for free](https://azure.microsoft.com/en-us/free/).
