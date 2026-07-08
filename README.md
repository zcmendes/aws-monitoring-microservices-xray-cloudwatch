![AWS](https://img.shields.io/badge/AWS-X--Ray-orange)
![EC2](https://img.shields.io/badge/Amazon-EC2-orange)
![Amazon CloudWatch](https://img.shields.io/badge/Amazon-CloudWatch-red)
![Python](https://img.shields.io/badge/Python-Flask-blue)
![Monitoring](https://img.shields.io/badge/Monitoring-Observability-success)
![Microservices](https://img.shields.io/badge/Microservices-Distributed-blueviolet)


# AWS Monitoring Microservice Architectures with AWS X-Ray and Amazon CloudWatch

## Overview

This repository documents the implementation of distributed tracing and monitoring for a microservices-based application using AWS X-Ray and Amazon CloudWatch.

The lab demonstrates how to instrument Python Flask applications, collect trace data, visualize service dependencies, and analyze end-to-end request performance.



## Architecture

### Three-tier Application Architecture

![Architecture](images/architecture.png)

The application consists of a three-tier architecture deployed in Amazon EC2 instances behind Application Load Balancers, with Amazon Aurora as the backend database.

---

### AWS X-Ray Instrumentation

![X-Ray Architecture](images/xray-architecture.png)

The application is instrumented with the AWS X-Ray SDK. Trace data is collected by the X-Ray daemon running on each EC2 instance and sent to AWS X-Ray and Amazon CloudWatch for distributed tracing and application performance monitoring.

---
## Services Used
## Objectives
## Environment
## Configuration
## Results
## Lessons Learned
