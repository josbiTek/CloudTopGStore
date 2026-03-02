# CloudTopGStore is full microservices-based e-commerce application designed, containerized, and orchestrated using Docker and Docker Compose.

# The system consists of **five core services**, all running as independent containers on the same Docker network:

# System Flow (How the Application Works)
1. Users browse products on the Cloud Top G Store frontend
2. Products are added to the Cart Service
3. The cart maintains temporary state
4. On checkout:
  #The Order Service creates a permanent order
  #The cart is cleared
  #Orders are stored persistently in MongoDB
5. Users can view their order history at any time
Carts are temporary. Orders are permanent.

**Frontend (Store UI)**
<img width="931" height="410" alt="image" src="https://github.com/user-attachments/assets/db332245-3aae-4846-a86d-739d7135dcd1" />

**Cart Service**
<img width="931" height="443" alt="image" src="https://github.com/user-attachments/assets/adebcee8-5a37-47e1-977c-adda3f0d7956" />

**Order Service**
<img width="928" height="317" alt="image" src="https://github.com/user-attachments/assets/62c4c6ff-d492-402c-b610-9d8d02fb2640" />

**MongoDB (Database)**
**Mongo Express (Database GUI)**
<img width="911" height="413" alt="image" src="https://github.com/user-attachments/assets/edc04564-d4cc-4fbb-b810-66cb4196f08b" />

