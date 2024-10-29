# Sonar Docker POC

## Description

Project for testing the configurations and capabilities of Sonarqube in a container mode. In order to test the viability of a self-mantained sonar instead of sonarcloud.

## Sonar

### Login

- `http://localhost:9000/`
  - User
    - admin
  - Password
    - admin

### Prometheus monitoring

- Health of your SonarQube installation
  - `api/system/health`
- Prometheus
  - `/api/monitoring/metrics`

### Plans & Pricing

- [Self-managed](https://www.sonarsource.com/plans-and-pricing/)
- [Sonarcloud](https://www.sonarsource.com/plans-and-pricing/sonarcloud/)

## PostgreSQL

### Login

- User
  - sonar
- Password
  - sonar

### Clients

- [DBeaver](https://dbeaver.io/)
- [pgAdmin](https://www.pgadmin.org/)
