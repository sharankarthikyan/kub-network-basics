## To start services using docker-compose:

- `docker-compose up -d`

## To stop services using docker-compose:

- `docker-compose down`

## To start all deployment and service:

- /kubernetes $ `kubectl apply -f=auth-deployment.yaml -f=auth-service.yaml -f=tasks-deployment.yaml -f=tasks-service.yaml -f=users-deployment.yaml -f=users-service.yaml -f=frontend-deployment.yaml -f=frontend-service.yaml`
