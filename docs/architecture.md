# Architecture

## Overview

The monitoring platform uses a lightweight architecture designed for low resource consumption.

## Components

### Raspberry Pi

Provides the compute platform running Linux services.

### Flask Application

Collects system information and provides the monitoring dashboard interface.

### Nginx

Acts as the web server and reverse proxy.

### Docker

Provides isolated application containers.

## Data Flow

System metrics are collected from the operating system and exposed through the Flask dashboard.

The web interface is served through Nginx.
