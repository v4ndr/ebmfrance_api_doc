# ebmfrance Clinical Practice Guidelines API Documentation

This repository hosts the OpenAPI (Swagger) documentation for the ebmfrance API.

## Overview

This API provides programmatic access to clinical practice guidelines, allowing search, filtering, and retrieval of guidelines by ID or facets. Access to the API is secured via API key authentication.

## Documentation

- The OpenAPI specification file is located at [`api_doc.yaml`](./api_doc.yaml).
- A Swagger UI frontend is included for easy interactive exploration of the API.

## How to View the Documentation Locally

To avoid CORS issues when opening the HTML file locally, it's recommended to run a simple HTTP server:

### Using Python 3

```bash
python3 -m http.server 8000
