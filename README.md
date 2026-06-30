It is a mini cloud platform that simulates the core services provided by cloud providers such as Amazon Web Services and Microsoft Azure, implemented using Docker.

The project consists of approximately nine main services/servers:

Web Frontend Server (web-frontend-server)
Application Backend Server (application-backend-server)
Relational Database Server (relational-database-server) – powered by MariaDB
Authentication and Identity Server (authentication-identity-server) – powered by Keycloak
Object Storage Server (object-storage-server) – powered by MinIO
Internal DNS Server (internal-dns-server) – powered by Bind9
Monitoring Server (monitoring-prometheus-server) – powered by Prometheus
Dashboard Server (monitoring-grafana-dashboard-server) – powered by Grafana
API Gateway/Proxy Server (api-gateway-proxy-server) – powered by Nginx

The main technologies used in this project include:

Docker and Docker Compose
Nginx
Flask
MariaDB
Keycloak
MinIO
Bind9
Prometheus
Grafana
