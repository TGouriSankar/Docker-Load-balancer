# 🚀 Caddy Load Balancer for Docker Containers

![Caddy Logo](https://media-exp1.licdn.com/dms/image/D4D12AQETgYlQ1uYutA/article-cover_image-shrink_720_1280/0/1667921877150?e=2147483647&v=beta&t=RpxyAlWN3z9KgSpzUXrwdCUquLAUGpejqopIhDuYYEM)

## 📦 Overview

This repository demonstrates how to set up **Caddy** as a load balancer for Docker containers. Caddy is a powerful, easy-to-use web server that provides automatic HTTPS and simple configuration, making it an excellent choice for load balancing.

## 🔍 What is Caddy?

**Caddy** is an open-source web server that:

- **Automatically obtains and renews SSL certificates** for your sites.
- Provides a simple and readable configuration file.
- Supports HTTP/2 and HTTP/3 for enhanced performance.
- Can easily act as a reverse proxy and load balancer for your applications.

## 🛠️ Why Use Caddy in Docker?

- **Simplicity:** Caddy’s configuration is straightforward, making it easy to set up and maintain.
- **Automatic HTTPS:** Ensures secure connections without the need for manual certificate management.
- **Scalability:** Effortlessly distribute traffic across multiple Docker containers, improving reliability and performance.

Caddy as a reverse proxy and load balancer in a similar way to how we set up Nginx. Caddy has several advantages, including automatic HTTPS configuration and a simpler configuration syntax.

## 🚀 Getting Started
---
 - Step 1: Create a Directory for Caddy Configuration

        Create a directory for your Caddy configuration:
        mkdir caddy-load-balancer
        cd caddy-load-balancer
---
- Step 2: Create a Caddyfile

    Create a Caddyfile in the caddy-load-balancer directory. This file will define your load balancing rules. Here’s an example configuration:
    check the Caddyfile code in the caddy-load-balancer directory
---
- Step 3: Create a Docker Compose File

    Create a docker-compose.yml file in the same directory to define your application services and Caddy:
    check the docker-compose.yml code in the caddy-load-balancer directory
---
- Step 4: Start the Services

    In the caddy-load-balancer directory, run:
  
            docker-compose up -d
---
- Step 5: Access Your Application

    Open your web browser and navigate to:
>    http://localhost \

 Caddy will route your requests through its reverse proxy, balancing the load between app1 and app2.

---
-    Step 6: Testing the Load Balancer

  As with the Nginx setup, you can refresh the page multiple times to see the load being balanced. Caddy will automatically handle the round-robin distribution of requests.

---
- Step 7: Stopping the Services

    To stop and remove the services, use:

        docker-compose down
---
Using Caddy as a reverse proxy and load balancer is a straightforward process, and it offers some conveniences like automatic HTTPS without needing extra configuration. 
