# Azure Web App Procedure
Creating a Basic Web App "Data Peeps" on Azure and publishing it as Code (Python Runtime Stack) to demonstrate the workflow.

Firstly, I will create an **App Service**  resource for the web app. I will be selecting "Code" as the publish method and configuring the runtime stack to Python and OS to Linux.

<img width="875" alt="Resource" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/7e7b1274-3b1b-4eff-a289-a656605e7a3d">


Upon visiting the URL for the app, it can be observed that the web app is up and running and is ready to receive deployment of the app's code.

<img width="924" alt="App Running URL" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/7a11d10f-589c-4ef2-ab1e-829592d70c36">


I'll use developer tools to create the code for the web application. In the Azure Cloud Shell, I'll create a virtual environment and install Flask.

<img width="462" alt="Venv + Flask" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/f2e43b80-af36-4215-b2be-ccdd28b92b9b">


Then I'll use the python interactive editor to write the simple code for the flask app.

<img width="549" alt="code" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/32267a96-654d-4b41-b48e-c211a5bd7f59">


Now I'll run a set of commands to set shell variables that contain our app's name, resource group name, plan name, sku, and location. These use different az commands to request the information from Azure; az webapp up needs these values to target our existing web app.

<img width="462" alt="Deploying" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/2e82f0c5-19bf-4d6a-8504-40217a593204">


Upon completion of deployment, the URL reflects our simple code on the web app landing page.

<img width="462" alt="Deployment complete" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/f8fdee38-4bb3-4576-b299-f4145846f4cd">

<img width="937" alt="Deployed" src="https://github.com/Abhishek-Dxt/Azure-Web-App/assets/71979171/508b4dc9-f0ed-4b52-856c-65cf9ce9f0c2">
