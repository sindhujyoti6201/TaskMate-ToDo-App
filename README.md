Development Phase:

Docker:
    - Dockerfile is created to make the custom app as an image.
    - docker-compose.yaml file is created to run the application locally.
    - Build the image and push it to DockerHub or any other private repository.

Kubernetes:
    - Running the Kubernetes Pods Locally using MiniKube and KubeCtl by:
    -- creating the deployment, services, configMap and secret
    -- open the external services by running the command: minikube service mongo-express-service
    -- updating the deployment to set replicas and deployment strategy.
    -- Run the pods locally 


Production Phase:
    -- Deploy it AWS EKS