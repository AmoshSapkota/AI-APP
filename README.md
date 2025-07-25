# An AI Teleprompter App

## Overview

This is an AI Teleprompter App designed to assist professionals to build confidence during presentations. It features a desktop application with teleprompter functionality and a set of microservices that handle various backend tasks.

## Project Structure

The project is organized into the following main components:

- **Microservices**: Each microservice is responsible for a specific functionality and is built using Spring Boot. The microservices include:

  - **API Gateway**: Handles routing and request management.
  - **Auth Service**: Manages user authentication and authorization.
  - **Payment Service**: Processes payments and manages orders.
  - **AI Content Service**: Generates content using AI for the teleprompter.
  - **Notification Service**: Sends notifications and manages email communications.
  - **Analytics Service**: Collects and analyzes user activity data.

- **Desktop App**: An Electron-based application that provides a user-friendly interface for the teleprompter functionality.

## Technologies Used

- **Backend**: Java, Spring Boot, Maven
- **Frontend**: React, Electron
- **Containerization**: Docker
- **Infrastructure**: Kubernetes, Terraform
- **CI/CD**: GitHub Actions, Argo CD
- **Monitoring**: Prometheus, Grafana, ELK Stack
