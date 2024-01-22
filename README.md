# Dockerized Web App Project

# Overview
This project demonstrates the containerization of a web application using Docker. The web application is packaged as a `.war` file, and the Dockerfile is provided to build a Docker image for deployment.

## Requirements

- Docker installed on the host machine.

## Steps to Reproduce

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/dockerized-web-app.git
   cd dockerized-web-app

2. **Unzip and Convert to .tar.gz:**

   ```bash
   unzip new-spot.war
   cd new-spot
   tar cvzf new-spot.tar.gz *

4. **Build Docker Image:**

    ```bash
    docker build -t new-spotimg .

5. **Run Docker Container:**

   ```bash
   docker run -d  --name myweb -p 9080:80 -d new-spotimg

6. **Access the Deployed Web Application:**
    Open your web browser and navigate to http://PublicIP:9080



    
    

   
