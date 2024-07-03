# Multilingual WebSphere

Welcome to Multilingual WebSphere, a comprehensive exploration of web API development across multiple programming languages. This project is designed to demonstrate the construction and operation of web APIs in Ruby, Rust, Go, and Python, all interfaced with a MySQL database. By examining each language in a web context, Multilingual WebSphere seeks to highlight the unique strengths, syntaxes, and performance characteristics inherent to each programming environment.

## Project Objective

The core objective of Multilingual WebSphere is to provide a comparative insight into the programming languages most commonly used in backend development. It aims to showcase:
- **Syntactic Variability**: How different languages handle similar tasks.
- **Performance Analysis**: Observing response times and resource usage across languages.
- **Library and Framework Utilization**: Understanding how different tools and libraries are used in typical API scenarios.

## Languages and Libraries Used

### Ruby

**Sinatra**: A DSL for quickly creating web applications in Ruby with minimal effort. Sinatra is chosen for its simplicity and readability, ideal for small web services.

### Rust

**Actix-web**: A powerful, pragmatic, and extremely fast web framework for Rust. Actix-web is utilized for its excellent performance and suitability for highly concurrent applications.

### Go

**net/http**: A robust package part of the Go standard library providing HTTP client and server implementations. It's known for its efficiency and straightforward approach in building web servers.

### Python

**Flask**: A lightweight and versatile web framework for Python, making it easy to build simple web applications quickly. Flask is used for its flexibility and ease of use.

## Project Features

- **Consistent API Endpoints**: Each language implementation offers the same API functionality, enabling direct comparison of handling and performance.
- **Docker Integration**: Each component of the project, including the MySQL database, is fully dockerized, ensuring easy setup and consistent runtime environments.
- **Database Interactions**: Demonstrates how each programming environment interacts with an SQL database, performing basic operations like querying data.

## Getting Started

### Prerequisites

Ensure Docker and Docker Compose are installed on your machine:

- [Install Docker](https://docs.docker.com/get-docker/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

### Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/multilingual-websphere.git
   ```

2. Change into the project directory:
   ```bash
   cd multilingual-websphere
   ```

3. Launch the application:
   ```bash
   docker-compose up --build
   ```


### Usage

Access the API endpoints through the following URLs once the services are running:
- `Ruby API: http://localhost:3000/`
- `Rust API: http://localhost:3001/`
- `Go API: http://localhost:3002/`
- `Python API: http://localhost:3003/`

