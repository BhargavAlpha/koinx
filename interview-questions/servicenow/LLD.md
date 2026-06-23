# ServiceNow - Low Level Design Interview Questions (2024-2026)

Real LLD questions asked in ServiceNow SSE, Senior SE interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design a Ticket Management System (ITSM)
**Frequency**: Very High (2024, 2025, 2026) - ServiceNow core domain
- Create, update, assign, resolve tickets
- Priority and severity levels
- SLA management and escalation
- Assignment rules (auto-assign)
- Workflow automation (state transitions)
- Audit trail and history
- Comments and attachments

### 2. Design a Workflow Engine
**Frequency**: High (2024, 2025)
- Define workflows with states and transitions
- Conditional branching
- Approval chains
- Parallel and sequential execution
- Timer-based triggers
- Error handling and retry
- Notification at state changes

### 3. Design a Change Management System
**Frequency**: Medium-High (2025, 2026)
- Change request creation
- Impact and risk assessment
- Approval workflows
- Scheduling and conflict detection
- Rollback planning
- Post-implementation review
- Integration with CI/CD

### 4. Design a Notification/Alert System
**Frequency**: Medium-High (2024, 2025)
- Multiple channels (email, SMS, in-app, push)
- Priority-based routing
- User preferences and subscriptions
- Rate limiting
- Template management
- Scheduled notifications
- Escalation rules

### 5. Design a Configuration Management Database (CMDB)
**Frequency**: Medium (2025, 2026) - ServiceNow specific
- CI (Configuration Item) management
- Relationships between CIs
- Discovery and auto-populate
- Impact analysis
- Version tracking
- Dependency mapping

### 6. Design a Knowledge Base System
**Frequency**: Medium (2024, 2025)
- Article CRUD with rich text
- Categories and tags
- Search with relevance ranking
- Version history
- Approval workflow for publishing
- Feedback (helpful/not helpful)
- Related articles

### 7. Design a Service Catalog
**Frequency**: Medium (2024, 2025)
- Service/product listing
- Category hierarchy
- Request submission with forms
- Approval routing
- Fulfillment tracking
- SLA for delivery
- Custom fields per catalog item

### 8. Design a Dashboard/Reporting System
**Frequency**: Medium (2025, 2026)
- Widget-based dashboards
- Multiple visualization types (chart, table, gauge)
- Data source configuration
- Refresh intervals
- Role-based visibility
- Export functionality
- Drill-down capability

### 9. Design a Rate Limiter
**Frequency**: Medium (2024, 2025)
- Token bucket / Sliding window
- Per-user and per-API limits
- Configurable thresholds
- Response headers (remaining, reset)
- Distributed implementation
- Burst handling

### 10. Design an Event-Driven Architecture
**Frequency**: Medium (2025)
- Event producers and consumers
- Event bus/broker
- Event schema registry
- Dead letter queue
- Event replay
- Ordering guarantees
- Idempotency

---

## ServiceNow-Specific Design Focus

ServiceNow interviews emphasize:
1. **ITSM Domain Knowledge** - Incident, Problem, Change management
2. **Workflow Automation** - Business process automation
3. **Multi-tenancy** - Enterprise SaaS architecture
4. **Integration Patterns** - REST APIs, webhooks, message queues
5. **Access Control** - Role-based and attribute-based
6. **Audit & Compliance** - Full traceability

---

## Design Patterns Emphasized at ServiceNow

| Pattern | Context |
|---------|---------|
| State Machine | Ticket lifecycle, Workflow states |
| Observer | Event notifications, Triggers |
| Strategy | Assignment rules, Routing |
| Chain of Responsibility | Approval chains, Escalation |
| Template Method | Standard workflows |
| Factory | Record/Object creation |
| Decorator | Adding capabilities to base records |
| Mediator | Service integration |

---

## Key Expectations

1. **Domain awareness** - Understand IT Service Management concepts
2. **Workflow-first thinking** - Everything is a process
3. **Extensibility** - Plugin architecture
4. **Multi-tenant design** - Data isolation
5. **API-first** - RESTful design principles
6. **Scalability** - Enterprise-grade performance
7. **Working code** - Clean OOP implementation expected
