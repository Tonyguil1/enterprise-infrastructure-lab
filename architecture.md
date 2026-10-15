# Enterprise Infrastructure Architecture

## Overview
This project simulates a small enterprise network
using four Ubuntu Server virtual machines.\

The infrastructure is hosted on an Ubuntu Linux
computer using Canonical Multipass.\

## Components

### Web Server
Hostname: web-server\
Purpose: Hosts internal web applications\
Planned software: Nginx, Docker\

### Database Server
Hostname: db-server\
Purpose: Stores application data\
Planned software: PostgreSQL\

### Monitoring Server
Hostname: monitor-server\
Purpose: Monitors the infrastructure\
Planned software: Prometheus, Grafana\

### Automation Server
Hostname: automation-server\
Purpose: Automates administration tasks\
Planned software: Ansible, Python\

## Network Design
All four virtual machines use the Multipass
virtual network.\

The instances communicate using their assigned
private IPv4 addresses.
