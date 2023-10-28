# Rental-Bikes-Azure-Deployment
Deploying the Rental Bikes Demand Prediction app to a Production Grade Server in Azure using CI/CD pipeline.

## Azure Container Registry
Create a new Azure container registry and save the `Login server` and `password`

## Command Prompt
Run the following commands:
* `docker build -t <Login Server>/<app name>:latest`
* `docker login <Login Server`
* docker push <Image Name>

## Azure Web App - Container
Configure a web app and choose the container option. Select the registry name and the image name and create the app.

After the app gets created, connect it with GitHub by navigating to the 'Deployment Center' Setting.