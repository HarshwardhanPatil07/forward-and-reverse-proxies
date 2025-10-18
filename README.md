# forward-and-reverse-proxies
![explaination](</forward-proxy/explaination.png>)

## Setup Instructions

1. Launch 3 EC2 instances (Ubuntu 20.04 recommended):
   - Backend Server
   - Forward Proxy
   - Reverse Proxy

2. Update security groups to allow necessary traffic:
   - Backend Server: Allow HTTP (80) from Reverse Proxy
   - Forward Proxy: Allow HTTP (8080) from your IP
   - Reverse Proxy: Allow HTTP (80) from anywhere

3. Follow the setup instructions in each directory to configure the services.