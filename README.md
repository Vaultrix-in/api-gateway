# 🚪 Vaultrix API Gateway

The secure entry point for all client requests. The API Gateway handles routing, authentication, and request proxying to the internal microservice mesh.

## 🛡️ Responsibilities
- **Request Routing**: Proxying traffic to User, Order, and Wallet services.
- **Security**: Centralized authentication and header management.
- **Performance**: Lightweight Node.js implementation optimized for high throughput.

## 📦 Dockerization
Uses a professional **Multi-Stage Docker build** to minimize footprint and reduce attack surface in production.


## 🛡️ Security & Quality
This repository is part of the Vaultrix Secure Software Development Lifecycle (SDLC):
- **SonarQube**: Static analysis & Quality Gate.
- **Snyk**: Open-source vulnerability scanning.
- **Trivy**: Container image security scanning.

## 🤝 Support
For internal support, please reach out to the DevOps team or open an issue in the **Vaultrix-Helm** repository.

---
© 2026 Vaultrix Platform. All rights reserved.
