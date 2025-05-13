# Web Infrastructure Design

This project focuses on understanding and designing basic web infrastructure systems. The goal is to visualize and explain how web applications work under the hood and identify common architectural issues.

---

## Task: 0. Simple Web Stack

Design a basic one-server web infrastructure to host a website reachable at `www.foobar.com`.

### Requirements:
- **1 domain name:** `foobar.com` with a `www` subdomain pointing to `8.8.8.8`
- **1 server** including:
  - Nginx (web server)
  - Application server (e.g., PHP, Node.js)
  - Application code (backend files)
  - MySQL database

### Key Concepts Explained:
- What is a server
- Role of a domain name
- Type of DNS record used
- Role of web server, app server, and database
- Protocol used to serve the website
- Infrastructure limitations: SPOF, downtime during updates, lack of scalability

Check the `0-simple_web_stack` file for the whiteboard screenshot and breakdown.

---
