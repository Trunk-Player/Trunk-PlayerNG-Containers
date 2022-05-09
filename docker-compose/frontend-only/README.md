# Frontend Only Container

This folder contains the configuration files for the frontend only.

## Getting Set Up

Follow these instructions.

### 1. Create Environment File

Copy the `.env.sample` to `.env` and change any environmental variables that are required. Optional variables can also be changed.

### 2. Start The Container

To run the frontend container, issue this command from the same directory as the `.env` and `docker-compose.prod.yml`:

    docker-compose -f docker-compose.prod.yml up