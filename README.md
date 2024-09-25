# 🚀 Load Balancer for Docker Containers

![Load Balancer Animation](https://www.uhost.com/images/pub/art/art_loadbalancing.gif)

## 📦 Overview

This repository demonstrates how to implement a **Load Balancer** for Docker containers, allowing you to efficiently distribute incoming traffic across multiple instances of your application. This setup enhances performance, increases availability, and improves redundancy.

## 🔍 What is Load Balancing?

Load balancing is the process of distributing network traffic across multiple servers or containers. By using a load balancer, you can:

- **Improve Performance:** Optimize resource use by distributing requests evenly.
- **Increase Availability:** Ensure your application remains accessible, even if one instance fails.
- **Scalability:** Easily add or remove instances based on demand without downtime.

## 🛠️ Why Use Load Balancing in Docker?

- **Container Management:** Docker makes it easy to deploy multiple instances of an application. Load balancing ensures these instances work together efficiently.
- **Microservices Architecture:** In a microservices environment, different services can be scaled independently, with load balancers managing traffic between them.
- **Simplified Deployment:** Load balancers facilitate the management of multiple containers, improving deployment speed and reliability.

## 🚀 Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/load-balancer-docker.git
   cd load-balancer-docker

2. **Run the Load Balancer:**
   - Ensure Docker and Docker Compose are installed, then run:

         docker-compose up -d
3. **Access Your Application:**
   - Open your browser and navigate to
   > http://localhost
   - To interact with your load-balanced application.

📜 License

This project is licensed under the MIT License.
[link](https://github.com/TGouriSankar/Docker-Load-balancer/blob/main/LICENSE)

