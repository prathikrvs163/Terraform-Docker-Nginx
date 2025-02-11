# 🚀 Terraform + Docker + Nginx Deployment

This project demonstrates how to use **Terraform** to deploy an **Nginx** web server inside a **Docker** container automatically.

## 📌 Features
- Uses **Terraform** to automate the deployment.
- Runs **Nginx** inside a **Docker container**.
- Exposes the server on **localhost:8080**.

## 🛠️ Prerequisites
- [Docker](https://docs.docker.com/get-docker/)
- [Terraform](https://developer.hashicorp.com/terraform/downloads)
- Git (optional, for version control)

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/<your-github-username>/terraform-docker-nginx.git
cd terraform-docker-nginx
```

### 2️⃣ Initialize Terraform

```sh
terraform init
```

### 3️⃣ Deploy Nginx with Terraform

```sh
terraform apply
```

Type yes when prompted.

### 4️⃣ Verify the Deployment
Open your browser and visit:

http://localhost:8080

You should see the Nginx welcome page.

### 5️⃣ Destroy the Deployment (Optional)

To remove the container, run:

```sh
terraform destroy
```

Type yes to confirm.

📝 Technologies Used

Nginx → Web server

Docker → Containerization

Terraform → Infrastructure as Code (IaC)

📜 License

This project is open-source under the MIT License.
