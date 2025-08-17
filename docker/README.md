# Node-RED Docker Setup
This folder provides two ways to run Node-RED using Docker:

1. Using the public `node-red-contrib-edgex-connector` package:

   Runs Node-RED with the publicly available connector package. Run the below snippet:
   ```bash
   docker compose -f docker-compose.public.yml up -d
   ```

   To stop the service: 
   ```bash 
   docker compose -f docker-compose.public.yml down
   ```

2. **For development purposes**:
    Run Node-RED with a local version of the `node-red-contrib-edgex-connector` package to test changes before publishing.  Run the below snippet:
   ```bash
   docker compose up -d
   ```

   To stop the service: 
   ```bash
   docker compose down
   ```