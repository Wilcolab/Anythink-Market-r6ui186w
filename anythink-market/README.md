# Anythink Market

This project is a simple Express server that listens on port 8001. It is set up to automatically restart on code changes using nodemon.

## Project Structure

```
anythink-market
├── src
│   └── server.js        # Entry point of the application
├── Dockerfile            # Dockerfile to build the server image
├── package.json          # npm configuration file
├── nodemon.json          # Configuration for nodemon
└── README.md             # Project documentation
```

## Getting Started

To get started with this project, follow the instructions below:

### Prerequisites

Make sure you have Node.js and Yarn installed on your machine.

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Wilcolab/Anythink-Market-r6ui186w.git
   cd Anythink-Market-r6ui186w
   ```

2. Install the dependencies:
   ```
   yarn install
   ```

### Running the Server

To start the server with automatic restarts on code changes, run:
```
yarn start
```

The server will be running on `http://localhost:8001`.

### Building the Docker Image

To build the Docker image, run:
```
docker build -t anythink-market .
```

### Running the Docker Container

To run the Docker container, use:
```
docker run -p 8001:8001 anythink-market
```

The server will be accessible at `http://localhost:8001` from your host machine.