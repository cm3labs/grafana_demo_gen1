# grafana_demo_gen1
Testing grafana. Using: docker, prometheus, grafana(cloud)

2024-09-09 :
- created branch gen1.1. Goal: local dockers -> grafana cloud dashboard
- realized I don't have a .gitignore. Doin that to ensure I don't expose any secrets ...

2024-09-07 :
- realized that prom wasn't getting node exporter data ... fixed port mapping and settings i ncompose.yaml and prometheus.yml


2024-09-06 : 
- created this github repo, made this change to the README.md, pushing first commit
- created prometheus.yml
- created Dockerfile
- tested cli run of grafana ... runs well on port 3000
- moved prometheus files to /prometheus, made /grafana
- added a docker compose compose.yaml, adding grafana docker image and prometheus image
- added 3 node-exporters ... unable to add as a Grafana data source. I gotta research why tomorrow.
- added a dashboard