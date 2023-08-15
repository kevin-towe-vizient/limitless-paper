# Kubernetes Deployments

## Deployment Configuration
  - This is where you define the agents Docker image, # of replicas and other config
## Dynamic Scaling
  - Implement k8s autoscaling wwith the Horizontal Pod Autoscaler(HPA) to scale agents based on CPU/memory usage or custom metrics.
## Persisted Workspaces
- (If) your builds require persistent storage, set up Persistent Volume Claims(PVCs) in your k8s configurations.