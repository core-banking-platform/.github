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

The platform is designed around microservice principles, with clear bounded contexts, service-level data ownership, and event-driven integration. It is intended to showcase practical system design in a banking domain where consistency, security, auditability, and scalability are critical. :contentReference[oaicite:1]{index=1}

## Architecture Principles
- Database per service
- API-first design
- Event-driven communication via message broker
- Idempotent write operations
- Controlled eventual consistency across services
- Auditability-first for financial data
- Independent deployment and scaling per service :contentReference[oaicite:2]{index=2}

## Core Services
The platform is organized into several major domains:
- **Business Services:** Customer, Account, Balance, Transaction, Transfer, Ledger, Product, Fee, Limit, Loan
- **Security Services:** Auth, RBAC, KYC, Fraud Detection
- **Support Services:** Notification, Audit, Reporting, Document, Scheduler, Workflow
- **Platform Services:** API Gateway, Kafka, Config, Service Discovery, Observability, Secrets Management :contentReference[oaicite:3]{index=3}

## MVP Scope
The initial MVP focuses on the minimum set of services required to make the system functional:
- API Gateway
- Auth Service
- Customer Service
- Account Service
- Balance Service
- Transaction Service
- Notification Service
- Audit Service
- Kafka
- PostgreSQL per service :contentReference[oaicite:4]{index=4}

## Purpose
This organization is used to group all repositories related to the Core Banking Platform into one place.  
Each service may live in its own repository, while this organization acts as the unified entry point for the whole system architecture, implementation, and future expansion. :contentReference[oaicite:5]{index=5}
