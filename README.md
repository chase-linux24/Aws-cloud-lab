# AWS Cloud Lab — Infrastructure Built From Scratch

## Overview
Designed and deployed a production-style AWS network architecture 
from scratch without using default VPC or auto-configuration wizards.

## Architecture
- **VPC** — Custom network `10.0.0.0/16`
- **Public Subnet** — `10.0.1.0/24` in us-east-1a
- **Internet Gateway** — Manually created and attached
- **Route Table** — Configured with `0.0.0.0/0` → IGW
- **Security Group** — SSH restricted to admin IP, HTTP open
- **EC2** — Ubuntu 22.04 t2.micro running Nginx web server

## Live Demo
http://44.222.238.68

## What I Built
- Designed full network architecture manually
- Wrote a bash system health monitor script
- Deployed Nginx web server accessible from public internet
- Applied least-privilege security group rules

## Skills Demonstrated
AWS | VPC | EC2 | Nginx | Bash | Linux | Network Security
