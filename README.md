# One-to-One Chat Application

A private messaging application built with **Java**, **Spring Boot**, **WebSocket**, **MongoDB**, **HTML**, **CSS**, **JavaScript**, and **Docker**. This project allows users to connect and chat privately in real-time.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Docker Setup](#docker-setup)
- [Screenshots](#screenshots)
  
## Features

- **User Authentication**: Users can log in and start a one-to-one chat session.
- **Real-Time Messaging**: Messages are sent and received instantly using WebSocket technology.
- **Persistent Data Storage**: Chat history is stored in MongoDB.
- **Responsive UI**: Built with HTML, CSS, and JavaScript for a seamless user experience.
- **User Connection Status**: Displays the current online status of users.
- **Dockerized Deployment**: Easily run the application and MongoDB using Docker.

## Technologies Used

- **Backend**: Java, Spring Boot, WebSocket
- **Database**: MongoDB
- **Frontend**: HTML, CSS, JavaScript
- **Containerization**: Docker, Docker Compose

## Getting Started

Follow these instructions to set up and run the application locally or in a Docker container.

### Prerequisites

- **Java 17** or higher
- **Maven** or **Gradle** for dependency management
- **Docker** and **Docker Compose** (for containerized deployment)

### Installation

- **Clone the Repository**  
   ```bash
   git clone https://github.com/subhash-varun/one-to-one-chat.git
   cd one-to-one-chat

### Docker Setup

To run the application and MongoDB with Docker:

1. **Build the Docker Images and Start Containers**  
   Make sure Docker is running, then run the following command:

   ```bash
   docker-compose up --build

2. **Stopping the Containers**  
   To stop the container use:

   ```bash
   docker-compose down

## Screenshots

![Application Interface](/app-preview.png)

![Login Page](/login-preview.png)

![Project Structure](/project-structure-preview.png)
