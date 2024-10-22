# Project Setup

## Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed.

## Installation and Running the Project

Follow these steps to install and run the server and client:

1. Clone the repository and navigate to the project folder:

    ```bash
    cd project-folder
    ```

2. Open a split terminal to run the server and client concurrently.

### Server Side

1. In the first terminal, navigate to the `server` directory:

    ```bash
    cd server
    ```

2. Install server dependencies:

    ```bash
    npm install
    ```

3. Run the server:

    ```bash
    npm run dev
    ```

### Client Side

1. In the second terminal, navigate to the `client` directory:

    ```bash
    cd client
    ```

2. Install client dependencies:

    ```bash
    npm install
    ```

3. Run the client:

    ```bash
    npm run dev
    ```

### Project Structure

- **server/**: Contains the backend code.
- **client/**: Contains the frontend code.

Both the server and client will run concurrently, with live reloading for development.
