# Core Banking Platform

A microservices-based core banking platform built for learning, architecture practice, and backend/distributed systems portfolio development.

## Overview
This project simulates the core capabilities of a retail banking system, including:
- Customer management
- Account management
- Balance handling
- Transaction processing
- Transfer orchestration
- Ledger and audit
- Authentication and authorization
- Notification and reporting

The platform is designed around microservice principles, with clear bounded contexts, service-level data ownership, and event-driven integration. It is intended to showcase practical system design in a banking domain where consistency, security, auditability, and scalability are critical. 

## Architecture Principles
- Database per service
- API-first design
- Event-driven communication via message broker
- Idempotent write operations
- Controlled eventual consistency across services
- Auditability-first for financial data
- Independent deployment and scaling per service 

## Core Services
The platform is organized into several major domains:
- **Business Services:** Customer, Account, Balance, Transaction, Transfer, Ledger, Product, Fee, Limit, Loan
- **Security Services:** Auth, RBAC, KYC, Fraud Detection
- **Support Services:** Notification, Audit, Reporting, Document, Scheduler, Workflow
- **Platform Services:** API Gateway, Kafka, Config, Service Discovery, Observability, Secrets Management 

## Purpose
This organization is used to group all repositories related to the Core Banking Platform into one place.  
Each service may live in its own repository, while this organization acts as the unified entry point for the whole system architecture, implementation, and future expansion. 
