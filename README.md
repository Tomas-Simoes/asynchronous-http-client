# Asynchronous HTTP Client

## Overview
The `HttpClient` class provides a simple way to send asynchronous HTTP requests to a RESTful API using the `aiohttp` library in Python. 
It supports SSL for secure communication and allows sending multiple requests concurrently to specified endpoints.

This client is designed to interact with the Riot Games API (or any other API with similar structure) and includes basic error handling and logging.

## Requirements
- Python 3.6 or later
- `aiohttp` (for asynchronous HTTP requests)
- `ssl` (for secure connections)
- `logging` (for logging HTTP request activity)
  
To install the required dependencies, run:

```bash
pip install aiohttp
