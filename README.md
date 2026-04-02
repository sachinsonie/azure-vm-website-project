# 🚀 Azure VM Website Deployment

## 📋 Project Overview
Deployed a live website on Microsoft Azure using a Linux Virtual Machine and Nginx web server.

## 🏗️ Architecture
Internet → NSG (Firewall) → Azure VM (Ubuntu) → Nginx → Website

## ☁️ Azure Services Used
- **Azure Virtual Machine** — Linux server (Ubuntu 24.04)
- **Azure Virtual Network** — Private network for the VM
- **Network Security Group** — Firewall rules
- **Public IP Address** — Makes website accessible worldwide

## 🛠️ Tech Stack
- OS: Ubuntu Linux 24.04 LTS
- Web Server: Nginx
- Cloud: Microsoft Azure

## 🔄 AWS Equivalent
| Azure | AWS |
|-------|-----|
| Virtual Machine | EC2 |
| VNet | VPC |
| NSG | Security Groups |
| Azure Portal | AWS Console |

## 📸 Screenshots


## 📝 Setup Steps
1. Created Resource Group
2. Deployed Ubuntu VM with Standard_B1s size
3. Configured NSG to allow ports 80 and 22
4. Connected via SSH
5. Installed and configured Nginx
6. Deployed custom HTML website

## 🎯 What I Learned
- Azure VM creation and configuration
- Linux server management
- SSH key authentication
- Nginx web server setup
- Azure Networking basics (VNet, NSG, Public IP)
