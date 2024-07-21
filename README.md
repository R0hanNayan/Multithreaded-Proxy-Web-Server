# Multithreaded Proxy Web Server

This project implements a multithreaded proxy web server that can handle multiple client requests concurrently, ensuring efficient and fast web browsing. The server is written in C and includes functionalities like request parsing and response caching.

## Features

- **Multithreading**: Handles multiple client requests simultaneously using threads.
- **Proxy Functionality**: Forwards client requests to target servers and relays responses back to clients.
- **Caching**: Stores responses to reduce latency for repeated requests.

## Technologies Used

- **Programming Language**: C

## Getting Started

### Prerequisites

- GCC compiler

### Installation

1. Clone the repository:

   git clone https://github.com/R0hanNayan/Multithreaded-Proxy-Web-Server.git

2. Navigate to the project directory:

   cd Multithreaded-Proxy-Web-Server

3. Compile the server:

   gcc -pthread -o proxy_server proxy_server_with_cache.c

### Running the Server

1. Start the proxy server:

   ./proxy_server <port_number>

2. Configure your browser or client to use the proxy server with the specified port.

## Usage

- **Proxy Requests**: The server will handle requests and cache responses for improved performance.
- **Thread Management**: Utilizes multithreading to manage multiple client connections efficiently.
