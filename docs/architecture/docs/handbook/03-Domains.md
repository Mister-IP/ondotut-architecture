# 03 - Domains

Status: Draft

Owner: Architecture Team

Last Updated: 2026-07-29

---

# Purpose

This document defines the functional domains of the OnDoTut platform.

A domain represents a high-level business capability.

Domains define ownership boundaries and responsibilities.

They are NOT implementation units.

Modules, services and APIs are designed inside domains.

---

# Domain List

## Workspace

### Purpose

Workspace is the root object of the platform.

Everything inside OnDoTut belongs to a Workspace.

### Responsibilities

- Workspace lifecycle
- General information
- Ownership
- Settings
- Isolation between workspaces

---

## Identity

### Purpose

Identity manages authentication, authorization and access control.

### Responsibilities

- Users
- Roles
- Permissions
- Authentication
- Authorization
- API Tokens
- Sessions

---

## Inventory

### Purpose

Inventory stores all managed objects.

### Responsibilities

- Devices
- Networks
- Sites
- Device Groups
- Interfaces
- IP Addresses
- Tags
- Labels
- Relationships

---

## Discovery

### Purpose

Discovery finds infrastructure components.

### Responsibilities

- Device discovery
- Network discovery
- Topology discovery
- Host availability
- Open port detection
- Identification
- Import discovered assets

---

## Monitoring

### Purpose

Monitoring continuously observes infrastructure health.

### Responsibilities

- Metrics
- Status
- Performance
- Availability
- Events
- Thresholds
- Health checks

---

## Documentation

### Purpose

Documentation maintains engineering knowledge.

### Responsibilities

- Device documentation
- Network documentation
- Notes
- Attachments
- Configuration history
- Change tracking

---

## Automation

### Purpose

Automation executes repeatable operational tasks.

### Responsibilities

- Workflows
- Jobs
- Scheduled Tasks
- Configuration deployment
- Bulk operations

---

## Notifications

### Purpose

Notification delivers system events.

### Responsibilities

- Email
- Telegram
- Webhooks
- Push Notifications
- Escalation

---

## Reporting

### Purpose

Reporting provides operational insights.

### Responsibilities

- Reports
- Dashboards
- Statistics
- Exports

---

## Integration

### Purpose

Integration connects OnDoTut with external systems.

### Responsibilities

- REST API
- Event API
- Import
- Export
- External platforms
- Connectors

---

## Administration

### Purpose

Administration manages the platform itself.

### Responsibilities

- Licensing
- Global Settings
- Audit
- Logs
- Backup
- System Health
- Maintenance

---

# Domain Principles

- Every capability belongs to exactly one domain.
- Domains communicate only through defined contracts.
- Domains must remain loosely coupled.
- Business rules belong inside their domain.
- Domains must not directly depend on vendor-specific implementations.

---

# Future Domains

The following domains may be introduced in future versions.

- AI Assistant
- Compliance
- Asset Lifecycle
- Configuration Management
- Secrets Management
- Billing
- Multi-Tenant Management
