
# 🚀 Nginx Load Balancer for Docker Containers

![Nginx Logo](https://pluspng.com/img-png/nginx-logo-png-php-logo-png-img-900-491-free-transparent-nginx-png-900x500.jpg)

## 📦 Overview

This repository demonstrates how to set up **Nginx** as a load balancer for Docker containers. Nginx is a high-performance web server and reverse proxy known for its stability, rich feature set, simple configuration, and low resource consumption.

## 🔍 What is Nginx?

**Nginx** (pronounced "engine-ex") is an open-source web server that:

- Acts as a reverse proxy for HTTP, HTTPS, and other protocols.
- Serves static files with high efficiency.
- Provides load balancing for distributed systems.
- Offers advanced features like caching, request buffering, and SSL termination.

## 🛠️ Why Use Nginx in Docker?

- **Performance:** Nginx is designed to handle a high number of simultaneous connections efficiently.
- **Scalability:** Easily scale your application by distributing traffic across multiple backend services.
- **Configuration Flexibility:** Offers powerful and flexible configuration options for complex routing needs.

## 🚀 Getting Started

**Step 1:** Create a Directory for Nginx Configuration

- Create a directory for your Nginx configuration:
  
      mkdir nginx-load-balancer
      cd nginx-load-balancer

**Step 2:** Create Nginx Configuration File

- Create a file named nginx.conf in the nginx-load-balancer directory: 
- check the conf file in the nginx-load-balancer directory

**Step 3:** Create a Docker Compose File

- Next, create a docker-compose.yml file in the same directory. Here’s how to configure it to include your application image along with Nginx:
- check the docker-compose.yml in the nginx-load-balancer directory

**Step 4:** Start the Services

- In the nginx-load-balancer directory, run:

      docker-compose up -d

**Step 5:** Access Your Application

- Open your web browser and navigate to:
> http://localhost
- This will route your requests through Nginx, which will load balance between app1 and app2.


**Step 6:** Testing the Load Balancer

-Refresh the page multiple times to see requests being distributed between app1 and app2. You can also check the logs for Nginx and your application containers to see how traffic is being handled:

    docker-compose logs nginx
    docker-compose logs app1
    docker-compose logs app2

**Step 7:** Stopping the Services
- To stop and remove the services, use:

      docker-compose down


