This repository showcases a production-ready, security-hardened environment designed for handling sensitive medical data. It bridges the gap between infrastructure automation and hardware-level security.
​Key Features
​Data Sovereignty: Implementation of LUKS (AES-256-XTS) encryption on a loop-device storage volume to ensure data-at-rest protection.  
​Automated Security Gates: Integrated GitHub Actions pipeline with Trivy scanning to block the deployment of images with HIGH or CRITICAL vulnerabilities.
​Hardened Network Perimeter: Custom SSH configuration on Port 2222, UFW firewalling, and CrowdSec intrusion prevention.
​Modern Edge Routing: Traefik v3 orchestrating Docker containers with automated Let's Encrypt SSL/TLS management.
​Observability Stack: Real-time monitoring and log management using Uptime Kuma and Dozzle.
​Tech Stack
​Cloud/OS: Debian/Ubuntu.
​Security: LUKS, CrowdSec, Trivy, UFW.
​Orchestration: Docker & Docker Compose.
​Reverse Proxy: Traefik v3.
​CI/CD: GitHub Actions.  
​A Note for Recruiters
​This project was developed for a freelance client to solve specific data sovereignty requirements. It demonstrates a commitment to security-first infrastructure and manual lifecycle management of encrypted volumes.
