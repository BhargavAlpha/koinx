# Salesforce - Low Level Design Interview Questions (2024-2026)

Real LLD questions asked in Salesforce MTS, LMTS, SMTS interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design a Message Queue System
**Frequency**: High (2024, 2025)
- Publish messages to topics/queues
- Consumer groups
- Message ordering
- At-least-once / at-most-once delivery
- Dead letter queue
- Priority-based consumption
- Asked specifically: "How do message queues fit in a system and how they help?"

### 2. Design a CRM System (Salesforce-specific)
**Frequency**: High (2025, 2026)
- Contact and Account management
- Lead tracking and conversion
- Opportunity pipeline
- Custom fields/objects
- Workflow automation triggers
- Role-based access control

### 3. Design a Task Management System
**Frequency**: Medium-High (2024, 2025)
- CRUD operations on tasks
- Priority and status management
- Assignment to users
- Due dates and reminders
- Comments and activity tracking
- Labels and filters

### 4. Design an Event-Driven Notification System
**Frequency**: Medium-High (2024, 2025)
- Event producers and consumers
- Multiple notification channels
- User preference management
- Rate limiting
- Retry with backoff
- Template-based messages

### 5. Design a Workflow Automation Engine
**Frequency**: Medium (2025, 2026)
- Define workflows with triggers and actions
- Conditional branching
- Sequential and parallel execution
- Approval workflows
- Error handling and rollback
- Audit trail

### 6. Design a Multi-Tenant Data Store
**Frequency**: Medium (2024, 2025)
- Tenant isolation
- Shared vs dedicated resources
- Query routing
- Data migration between tenants
- Performance isolation
- Metadata-driven schema

### 7. Design a Rate Limiter
**Frequency**: Medium (2025)
- Token bucket / Sliding window
- Per-tenant rate limiting
- API-level and user-level limits
- Configurable policies
- Grace period handling

### 8. Design an API Gateway
**Frequency**: Medium (2024, 2025)
- Request routing
- Authentication/authorization
- Rate limiting
- Request/response transformation
- Caching
- Circuit breaker

### 9. Design a Cache with Eviction Policies
**Frequency**: Medium (2024, 2025)
- LRU / LFU eviction
- TTL support
- Write-through / Write-back strategies
- Cache invalidation
- Thread safety
- Size-based limits

### 10. Design a Logging and Monitoring System
**Frequency**: Medium (2025, 2026)
- Structured logging
- Multiple severity levels
- Centralized log aggregation
- Search and filter capabilities
- Alerting rules
- Dashboard visualization

---

## Design Patterns Emphasized at Salesforce

| Pattern | Context |
|---------|---------|
| Observer | Event-driven architecture |
| Strategy | Workflow action types |
| Factory | Object/record creation |
| Builder | Complex query construction |
| Chain of Responsibility | Approval workflows |
| Mediator | Inter-service communication |
| Template Method | Standard workflow steps |

---

## Key Expectations

1. **Multi-tenancy awareness** - Design for shared infrastructure
2. **Workflow-oriented thinking** - Automation is core to Salesforce
3. **Data modeling** - Entity relationships and custom metadata
4. **API design** - RESTful best practices
5. **Scalability** - Handle enterprise-scale data
6. **Security** - Role-based access, data isolation
7. **Extensibility** - Plugin/extension points for customization
