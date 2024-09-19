# Netflix_Clone

## Overview
This project deploys a microservices architecture using Docker, AWS EC2, and Terraform.

## Architecture
- Nginx as a reverse proxy and load balancer
- NetflixFrontend as a Node.js app
- NetflixMovieCatalog as a Flask API

## Setup Instructions
1. Clone the repository
2. Navigate to the terraform directory and run `terraform apply`
3. Set up Route 53 for domain management

## Deployment Process
- Changes to the main branch trigger CI/CD via GitHub Actions.

## CI/CD Explanation
- Docker images are built and pushed to Docker Hub.
- Deployment to EC2 is automated through GitHub Actions.
