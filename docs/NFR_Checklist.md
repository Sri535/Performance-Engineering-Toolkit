# 📋 Enterprise Non-Functional Requirements (NFR) Checklist

> A comprehensive checklist for collecting, validating, and documenting Non-Functional Requirements before starting Performance Engineering activities.

---

# 📑 Table of Contents

1. Introduction
2. Why NFRs Matter
3. Application Information
4. Business Requirements
5. User Workload
6. Performance Requirements
7. Scalability Requirements
8. Availability & Reliability
9. Infrastructure Requirements
10. Monitoring Requirements
11. Security Considerations
12. Test Environment
13. Risks & Assumptions
14. NFR Validation Checklist

---

# Introduction

Non-Functional Requirements (NFRs) define how a system should perform under expected and peak workloads. They are the foundation of successful Performance Engineering.

Without clearly defined NFRs, it is difficult to determine whether an application has met its performance objectives.

---

# Why NFRs Matter

NFRs help teams:

- Define measurable success criteria
- Build realistic workload models
- Establish Service Level Agreements (SLAs)
- Identify scalability expectations
- Plan capacity requirements
- Reduce production performance risks

---

# Application Information

| Item | Details |
|------|---------|
| Application Name | |
| Application Owner | |
| Business Domain | |
| Application Type | Web / API / Mobile / Batch |
| Technology Stack | |
| Deployment Platform | |
| Environment | Dev / QA / UAT / Production |

---

# Business Requirements

- [ ] Business objectives documented
- [ ] Critical user journeys identified
- [ ] Peak business periods identified
- [ ] Business priorities documented

Examples:

- User Login
- Product Search
- Checkout
- Payment
- Order Status

---

# User Workload

## Expected Users

| Metric | Value |
|---------|------|
| Concurrent Users | |
| Peak Users | |
| Daily Active Users | |
| Monthly Active Users | |

---

## Traffic Profile

- [ ] Peak Hours identified
- [ ] Average Load identified
- [ ] Growth Forecast available
- [ ] Seasonal Peaks documented

---

# Performance Requirements

| Metric | Target |
|---------|---------|
| Login Response Time | |
| Search Response Time | |
| API Response Time | |
| Checkout Response Time | |
| Batch Completion Time | |

---

# Throughput Requirements

| Metric | Target |
|---------|---------|
| TPS | |
| Requests/sec | |
| Transactions/hour | |

---

# Error Rate

| Metric | Target |
|---------|---------|
| Error Percentage | |
| Timeout Percentage | |

---

# Scalability Requirements

- [ ] Horizontal scaling supported
- [ ] Vertical scaling supported
- [ ] Auto Scaling enabled
- [ ] Maximum supported users documented

---

# Availability & Reliability

| Requirement | Target |
|-------------|---------|
| Availability | |
| Recovery Time Objective (RTO) | |
| Recovery Point Objective (RPO) | |
| Failover Time | |

---

# Infrastructure Requirements

Collect

- CPU
- Memory
- Disk
- Network
- JVM
- Containers
- Kubernetes Nodes
- Database Configuration

---

# Monitoring Requirements

Application

- [ ] Response Time
- [ ] Error Rate
- [ ] Throughput

Infrastructure

- [ ] CPU
- [ ] Memory
- [ ] Disk

JVM

- [ ] Heap
- [ ] Garbage Collection
- [ ] Thread Count

Database

- [ ] Slow Queries
- [ ] Locks
- [ ] Connection Pool

---

# Security Considerations

- [ ] Authentication
- [ ] Authorization
- [ ] Rate Limiting
- [ ] Encryption
- [ ] Sensitive Data Handling

---

# Test Environment Checklist

- [ ] Production-like environment
- [ ] Monitoring enabled
- [ ] Test accounts available
- [ ] Test data prepared
- [ ] Logging enabled

---

# Risks & Assumptions

## Risks

- Incomplete workload information
- Shared environment
- Limited monitoring
- Third-party dependency constraints

## Assumptions

- Stable environment
- Accurate production estimates
- Monitoring availability
- Sufficient test data

---

# NFR Validation Checklist

## Requirements

- [ ] Response time targets documented
- [ ] Throughput targets documented
- [ ] User load documented
- [ ] Error thresholds documented

## Monitoring

- [ ] APM configured
- [ ] Infrastructure monitoring enabled
- [ ] Database monitoring enabled

## Workload

- [ ] User distribution defined
- [ ] Think time documented
- [ ] Peak load identified

## Approval

- [ ] Business Owner
- [ ] Product Owner
- [ ] Architect
- [ ] Performance Engineer

---

# Common Mistakes

❌ Starting scripting before collecting NFRs

❌ Assuming production workload

❌ Ignoring seasonal traffic

❌ Missing SLA definitions

❌ Testing without monitoring

❌ Unrealistic user distribution

---

# Best Practices

✔ Validate NFRs before test planning.

✔ Ensure all stakeholders agree on performance targets.

✔ Keep NFRs measurable and realistic.

✔ Review NFRs for every major release.

✔ Update workload assumptions periodically.

---

# Related Documents

- Enterprise Performance Engineering Guide
- Performance Engineering Checklist
- Root Cause Analysis Playbook
- Capacity Planning Guide
- Performance Metrics Reference

---

# About

This checklist is part of the **Performance Engineering Toolkit** project.

Its goal is to help teams collect complete and measurable Non-Functional Requirements before initiating Performance Engineering activities.

⭐ If this guide is useful, please consider starring the repository.