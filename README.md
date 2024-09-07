# About #
This repository has de responsability of maintain the IAC code to deploy all the struture to the cluster EKS that will receive the open metadata application.

### Requirements
Unix based OS
2 cores and 8 GB machine

### Local Deploy

Requirements:
- docker
- docker compose

```bash
docker compose up --detach
```
Access http://your-docker-local-host:8585 to acces open-metadata interface
Username: admin@openmetadata.org
Password: admin

Access http://your-docker-local-host:8080 to acces airflow interface
`Username: admin`
`Password: admin`

Full deploy tutorial and FAQ: https://docs.open-metadata.org/latest/quick-start/local-docker-deployment