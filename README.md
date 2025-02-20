Name: Mohammad Faisal Khan

Email-id: mdfaisalk15@gmail.com

# **Online Shop - Hackathon**  
**Phase 1 Submission**  

## **Project Overview**  
This project is a part of the Online Shop Hackathon, where I successfully deployed an online shop application using Docker and AWS EC2.  

## **Project Details**  

1. **Repository Setup**  
   - Forked the **Online Shop** repository.  
   - Cloned the repository into my **AWS EC2 instance**.  

2. **Dockerization**  
   - Created a **Dockerfile** to containerize the application.  
   - Built a Docker image named **"shop"** using:  
     ```bash
     docker build -t shop .
     ```
   - Ran the Docker container using:  
     ```bash
     docker run -d --name shopapp -p 3000:3000 shop
     ```

3. **Container Management**  
   - Docker container name: **shopapp**  
   - Used essential Docker commands:  
     ```bash
     docker images         # List images
     docker ps             # List running containers
     docker ps -a          # List all containers
     docker stop shopapp   # Stop container
     docker rm shopapp     # Remove container
     docker system prune   # Clean up unused Docker resources
     docker rmi $(docker images -aq)  # Remove all images
     docker rm $(docker ps -aq)       # Remove all containers
     ```

4. **Linux Commands Used**  
   - `ls`, `pwd`, `mkdir`, `vim`  

5. **Configuration Changes**  
   - Edited `vite.config.js` to set the **server port to 3000**.  

6. **Deployment**  
   - Followed **DevOps best practices** to deploy the application on an **AWS EC2 instance**.  
   - The application is successfully running on **port 3000**.  

## **Conclusion**  
By implementing Docker and DevOps methodologies, I have efficiently deployed the Online Shop application in a containerized environment on AWS EC2.  
<img width="940" alt="image" src="https://github.com/user-attachments/assets/f677b5c8-cc7e-4aef-b12b-6e6e37ec0aa6" />



