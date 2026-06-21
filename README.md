![CI/CD](https://github.com/not1llusion/first-app-ci-cd-deploy/actions/workflows/deploy.yml/badge.svg)
# First DevOps app.

This project demonstrates a CI/CD pipeline using simple Python web application. 

## Stack
- Python 3.11
- Docker + Docker Compose
- GitHub Actions (CI/CD)
- Nginx (reverse proxy)

## How it works
1. Developer pushes code to main branch
2. GitHub builds and pushes docker image to Docker Hub
3. App is automatically upload to VPS

## Infrastructure
- VPS: play2go (Ubuntu 22.04)
- Domain: notillusion.duckdns.org
- HTTPS via Let's Encrypt

## Live Demo
[notillusion.duckdns.org](https://notillusion.duckdns.org:8080)
