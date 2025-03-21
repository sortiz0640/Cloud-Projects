
# DafoProject 🌐 Cloud-Based Game Server and Website
This project implements a cloud-based infrastructure to host a game server and a website for managing game assets and documentation. The architecture is deployed on Microsoft Azure, ensuring scalability, security, and efficient access control via a VPN gateway. 

## 📁 Project Overview
The system consists of the following key components:

- Virtual Machine (Windows Server 2022): Hosts the game server and the website.
- Game Server: Runs a Minecraft Server, allowing clients to connect and play using the server IP address and port 25565.
- Website: Provides access to game assets and documentation for players.
- VPN Gateway: Ensures secure remote access for authorized users.
- Cloud Infrastructure: Designed with Azure Virtual Network, subnets, and network security groups (NSG) to manage access control.

## ⚙️How It Works 
1. Clients connect to the VPN to securely access the system.
2. They can download resources and documentation from the website.
3. Players can connect to the game server to play online.
4. This architecture ensures a secure and efficient gaming environment, leveraging cloud computing for optimal performance and reliability.

## 🔷 Infrastructure Diagram
![Cloud Diagram](https://github.com/sortiz0640/Cloud-Projects/blob/main/DafoProject/resources/cloud-diagram.png)
> Created using [Eraser.io](https://www.eraser.io/diagramgpt)

## 💿 Demo
![Demo](https://github.com/sortiz0640/Cloud-Projects/blob/main/DafoProject/resources/demo/DafoProject.gif)
> This project is fully hosted in a private learning environment. Its resources are not deployed to the public

