# Start by cloning the app.py 
https://github.com/sojoudian/clo835_s24/blob/master/project-2/app.py

# Create a Dockerfile

# Build docker
docker build -t your-dockerhub-username/app-name:v1 .

# Push your Docker image
docker push your-dockerhub-username/app-name:v1

# Write kubernetes deployment.yaml and services.yaml

# Apply kubernetes manifests
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

# Testing the Application
Access your application via NodePort: http://<minikube-ip>:30303
