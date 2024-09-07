# grafana_demo_gen1
Testing grafana. Using: docker, prometheus, grafana

2024-09-06 : 
- created this github repo, made this change to the README.md, pushing first commit
- created prometheus.yml
- created Dockerfile
- tested cli run of grafana ... runs well on port 3000
- moved prometheus files to /prometheus, made /grafana
- added a docker compose compose.yaml, adding grafana docker image and prometheus image
- added 3 node-exporters ... unable to add as a Grafana data source. I gotta research why tomorrow.