# VDI Application

## Overview

This repository contains the code and resources for the VDI (Virtual Desktop Infrastructure) application, which features both backend and frontend components.

## Project Structure

The structure of the project is divided into two main parts:
- **Backend**: The server-side application built using FastAPI.
- **Frontend**: The client-side application built using React.

## Features
- User authentication
- Resource management
- Virtual desktop provisioning

## Getting Started

### Prerequisites
- Python 3.x
- Node.js
- Docker

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/udayponnaganti/VDI.git
   cd VDI
   ```

2. Set up the backend:
   - Navigate to the `backend` directory
   - Install dependencies from `requirements.txt`: 
     ```sh
     pip install -r requirements.txt
     ```

3. Set up the frontend:
   - Navigate to the `frontend` directory
   - Install dependencies:
     ```sh
     npm install
     ```

4. Run the application using Docker:
   ```sh
   docker-compose up --build
   ```

## Usage

Once the application is running, access the frontend at `http://localhost:3000`. The backend API can be accessed at `http://localhost:8000`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.