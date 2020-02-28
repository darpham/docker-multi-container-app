# docker-multi-container-app
Utilizing docker containers to deploy a Fibonacci web-app

CI/CD tool: TravisCI

Technology Stack:
Docker
Nginx
React
Express
PostgreSQL
Redis

TravisCI:
Upon PR merge to Master
Build test image and tests the code
Build production image and upload to Docker Hub
Push project to AWS Elastic Beanstalk for deployment
.
