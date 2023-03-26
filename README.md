# React Gym Management App

![React](https://img.shields.io/badge/React-17.0.2-blue?style=flat-square&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-14.17.5-green?style=flat-square&logo=node.js)
![npm](https://img.shields.io/badge/npm-6.14.14-red?style=flat-square&logo=npm)
![Docker](https://img.shields.io/badge/Docker-20.10.8-blue?style=flat-square&logo=docker)

## Description

This is a gym management application built with React. It allows gym owners to manage their clients, trainers, and schedules.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/username/react-gym-management-app.git
   ```

2. Install dependencies:

   ```
   npm install
   ```

## Usage

To run the application:

```
npm start
```

The application will be available at `http://localhost:3000`.

## Docker

To run the application using Docker:

1. Build the Docker image:

   ```
   docker build -t react-gym-management-app .
   ```

2. Run the Docker container:

   ```
   docker run -p 3000:3000 react-gym-management-app
   ```

The application will be available at `http://localhost:3000`.

## Files

- `src/components/Dashboard.jsx`: The dashboard component.
- `src/components/Footer.jsx`: The footer component.
- `src/components/Login.jsx`: The login component.
- `src/components/Navbar.jsx`: The navbar component.
- `src/components/NotFound.jsx`: The 404 not found component.
- `src/components/Register.jsx`: The register component.
- `src/components/Sidebar.jsx`: The sidebar component.
- `Dockerfile`: The Dockerfile for building the Docker image.