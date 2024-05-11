# Product Microservice

## Overview

This project is a microservice that provides endpoints for retrieving products.

## Features

- Retrieve Products

## Usage

1. Clone the repository:

   ```bash
   git clone <https://github.com/avd1729/Product-Microservice>
   ```

2. Navigate to the project directory:

   ```bash
   cd Product-Microservice
   ```

3. Build the Docker image:

   ```bash
   docker build -t products .
   ```

4. Run the Docker container:

   ```bash
   docker run -p 5001:5001 products
   ```

### Endpoints

GET /products: Retrieve all products.
