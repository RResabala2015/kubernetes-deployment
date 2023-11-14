# Kubernetes Deployment 🚀

## 📖 Description

This project offers various configurations for continuous deployment to Kubernetes using Google Cloud Platform. 🌐 Designed to simplify and automate the deployment process, it's ideal for developers and system administrators working with Kubernetes on GCP.

## 🗂 Project Structure

- **`/docker/bin`**: Contains shell scripts like `consume_queue.sh` for Docker-related operations.
- **`/google-cloud`**: Holds the `production.cd.cloud-build.yaml` file for Google Cloud build configurations.
- **`/k8s/production`**:
  - `config.yaml`: Base Kubernetes configuration file.
  - `cronjob-consume-queue.yaml`: Kubernetes cron job for queue consumption tasks.
  - `cronjob.yaml`: General Kubernetes cron jobs.
  - `deployment.yaml`: Kubernetes deployment configurations.
  - `hpa.yaml`: Horizontal Pod Autoscaler configurations.
  - `ingress.yaml`: Ingress resource definitions.
  - `namespace.yaml`: Namespace specifications for Kubernetes.
  - `service.yaml`: Service definitions for exposing applications.

## 🛠 Installation & Deployment

To deploy the configurations to your Kubernetes cluster on GCP, follow these steps:

```bash
# Clone the repository
git clone https://github.com/RResabala2015/kubernetes-deployment.git

# Navigate to the production configurations
cd k8s/production

# Apply the Kubernetes configurations
kubectl apply -f deployment.yaml
```

## 📜 License

This project is licensed under the terms of the [MIT License](https://github.com/RResabala2015/kubernetes-deployment/blob/main/LICENSE).
