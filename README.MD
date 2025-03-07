# Flask Application Monitoring with Prometheus and Grafana

## Overview
This project demonstrates how to set up monitoring for a Flask web application using Prometheus and Grafana. The monitoring system allows you to track, collect, and visualize important application metrics in real-time.

## What's Included

### 1. Setting up Prometheus, Grafana, and our Flask app
- Installation and configuration of Prometheus for metrics collection
- Installation and configuration of Grafana for visualization
- Integration with a Flask application to expose custom metrics
- Docker-compose setup for easy deployment of all components

### 2. Configuring metrics in Prometheus
- Setting up Prometheus scrapers to collect metrics from the Flask app
- Defining custom metrics specific to your application needs
- Configuring alert rules for critical thresholds
- Setting up proper retention and storage policies

### 3. Visualizing metrics in Grafana
- Creating dashboards to display important application metrics
- Setting up panels for different visualization types (graphs, gauges, etc.)
- Configuring alerts based on metric thresholds
- Creating custom queries using PromQL

## Getting Started
1. Clone this repository
2. Run the Docker Compose setup: `docker-compose up -d --build`
3. Access Prometheus at `http://localhost:9090`
4. Access Grafana at `http://localhost:3000` (default credentials: admin/password). Modify grafana.ini if you want to change the password
5. Access the Flask application at `http://localhost:5001`

## Requirements
- Docker and Docker Compose
- Python 3.x (for local development)
- Network connectivity between all components

## Additional Resources
- [Prometheus Documentation](https://prometheus.io/docs/)
- [Grafana Documentation](https://grafana.com/docs/)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Monitor Web Apps Using Grafana and Prometheus](https://www.youtube.com/watch?v=y6bfr72Nntw&list=PLO7V73jmRfdDksHoppAWwKcxb2Jsov2hp&index=2&ab_channel=FEWV)