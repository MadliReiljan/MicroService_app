# Microservices Project

## Description
This project is a large, scalable app built using a microservices architecture, following a tutorial. 
It covers advanced concepts in microservices, including solving concurrency issues, deploying apps to the cloud using Docker and Kubernetes, and building a Server-Side Rendered React app. 
The focus is on production-level, scalable code designed for enterprise environments, with reusable code across multiple Express servers.

This project has been created by the help of this tutorial creator: https://www.youtube.com/@BeALearnerofficial/videos

## Key Features

* Microservices Architecture: Each service is independently deployable, scalable, and interacts through an event bus.
* Event-Based Architecture: Communication between services is handled via asynchronous events to ensure fast, efficient data exchange.
* Server-Side Rendering (SSR): The React app renders data from the microservices, optimizing performance and SEO.
* Scalability & Concurrency: Solutions for distributed systems, concurrency issues, and challenges like unordered event streams.
* Docker & Kubernetes: Containerized services and deployed the entire architecture to the cloud.
* Custom NPM Packages: Shared code between services for reusability and cleaner architecture.
* Production-Ready Code: The project emphasizes best practices to write maintainable, scalable, and production-level code.

## What I have learned

* Architect large, scalable apps using microservices.
* Deploy multi-service apps using Docker and Kubernetes.
* Solve distributed systems concurrency issues.
* Write server-side rendered React apps.
* Communicate data between services using a fast event bus.
* Write comprehensive tests for microservices.

## Used Tech

* Backend: Node.js, Express, Microservices Architecture
* Frontend: React with Hooks, Server-Side Rendering
* Database: MongoDB/PostgreSQL
* DevOps: Docker, Kubernetes, CI/CD Pipelines
* Other Tools: NPM, Custom Packages

## Installation

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

* Git
* Node.js (v20.11.1)
* npm (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/MadliReiljan/MicroService_app
```
### Installation

Every folder needs its own dependencies installation (exept client folder)

For comments, posts and query folder:
```bash
npm init -y
```
```bash
npm install express cors axios nodemon
```

For event-bus and moderation folder:
```bash
npm init -y
```
```bash
npm install express axios nodemon
```

### Running the Project

```bash
 npm start
```
