# Hello World App

A simple Python application with CI/CD pipeline using GitHub Actions and Docker.

## Features

- Python "Hello World" application
- Unit tests with pytest
- Docker containerization
- CI/CD pipeline with GitHub Actions

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/hello-world-app.git
   cd hello-world-app

## Docker Deployment

### Build the image:

    ```bash
    docker build -t hello-world-app .
```
 ### Run the container:

   ```bash
   docker run hello-world-app
```

## Summary

This lightweight project demonstrates:
- Version control with Git/GitHub
- Containerization with Docker
- Automated testing and deployment with GitHub Actions
- Local deployment verification
- The entire pipeline is triggered with each push to GitHub


## You can extend this by:
- Adding more complex application logic
- Deploying to a cloud provider
- Adding more comprehensive tests
- Implementing multi-stage Docker build for production