# Docker Basic Practice

Simple project to practice Docker build, push, and run.

## Build Image
```bash
docker build -t welcome-app .
Run Container
docker run -d -p 5000:5000 welcome-app
Push to Docker Hub
docker tag welcome-app anmolrajput/welcome-app:latest
docker push anmolrajput/welcome-app:latest