# 🚀 HAProxy Load Balancer for Docker Containers

![HAProxy Logo](https://www.ochobitshacenunbyte.com/wp-content/uploads/2019/12/logo-haproxy.png)

## 📦 Overview

This repository demonstrates how to set up **HAProxy** as a load balancer for Docker containers. HAProxy is a high-performance TCP/HTTP load balancer that distributes incoming requests to multiple backend servers, ensuring high availability and fault tolerance for your applications.

## 🔍 What is HAProxy?

**HAProxy** (High Availability Proxy) is a popular open-source software that provides load balancing and proxy services for web applications. Key features include:

- **High Performance:** Capable of handling a large number of concurrent connections.
- **Session Persistence:** Maintains user sessions across requests for a consistent experience.
- **Health Checks:** Monitors the health of backend servers to route traffic only to healthy instances.

## 🛠️ Why Use HAProxy in Docker?

- **Efficient Resource Utilization:** Distributes traffic evenly across multiple Docker containers, optimizing resource usage.
- **Scalability:** Easily scale your application by adding or removing container instances.
- **Simplified Management:** Centralizes traffic management, making it easier to maintain and monitor your applications.

## 🚀 Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/haproxy-load-balancer.git
   cd haproxy-load-balancer

2. **Run the Load Balancer:**
- Ensure Docker and Docker Compose are installed, then run:

        docker-compose up -d
3.Access Your Application:

> Open your browser and navigate to http://localhost to access your application through the HAProxy load balancer.

📜 License

This project is licensed under the MIT License.



