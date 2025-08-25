# nginx-demo

This project showcases how to serve a static HTML landing page through a lightweight Node.js (Express) server, containerize the application using Docker, and run multiple app instances with Docker Compose. These instances are then load balanced using NGINX, demonstrating a common production-ready architecture where NGINX acts as a reverse proxy to efficiently distribute incoming traffic across multiple servers, improve availability, and enable horizontal scaling.

## Project Structure

- **index.html** → A simple landing page with a header, navigation, card grid layout, and footer.
- **server.js** → Node.js Express server that serves the static HTML file.
- **package.json** → Project dependencies and scripts.
- **docker-compose.yml** → Defines multiple app instances for load balancing.
- **images/** → Contains assets used in the landing page.

## Features

- Responsive landing page (HTML + CSS).
- Node.js Express server to serve static files.
- Docker Compose to spin up multiple app instances (`App1`, `App2`, `App3`).
- Ready to integrate with **NGINX** for load balancing.

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- [Docker](https://www.docker.com/) & [Docker Compose](https://docs.docker.com/compose/) installed
