# Amazon - Low Level Design Interview Questions (2024-2026)

Real LLD/Machine Coding questions asked in Amazon SDE interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design a Parking Lot System
**Frequency**: Very High (2024, 2025)
- Multiple floors, different vehicle types (bike, car, truck)
- Assign nearest available spot
- Pricing based on duration and vehicle type
- Entry/exit gate management
- Handle concurrency for spot assignment

### 2. Design an Online Shopping System (Amazon-like)
**Frequency**: High (2024, 2025)
- Product catalog with categories
- Shopping cart management
- Order placement and tracking
- Inventory management
- Payment processing (multiple methods)
- Notification system for order updates

### 3. Design a Ride-Sharing Service (Uber/Ola)
**Frequency**: High (2024, 2025, 2026)
- Rider and driver matching
- Trip management (request, accept, complete, cancel)
- Fare calculation with surge pricing
- Real-time location tracking
- Rating system

### 4. Design a Library Management System
**Frequency**: High (2024, 2025)
- Book CRUD operations
- Member management
- Issue/Return books with due dates
- Fine calculation
- Search by title, author, ISBN
- Reservation system

### 5. Design an Elevator System
**Frequency**: Medium-High (2024, 2025)
- Multiple elevators in a building
- Scheduling algorithm (SCAN, LOOK)
- Handle concurrent requests
- Priority for emergency/VIP
- Optimize for minimal wait time

### 6. Design a Food Delivery System
**Frequency**: High (2025, 2026)
- Restaurant management
- Menu browsing and ordering
- Delivery partner assignment
- Order tracking (real-time status)
- Rating and review system
- Estimated delivery time calculation

### 7. Design a Notification Service
**Frequency**: Medium (2024, 2025)
- Multiple channels (Email, SMS, Push)
- Priority-based delivery
- Template management
- Rate limiting
- Retry mechanism with exponential backoff
- User preferences for notification types

### 8. Design a Task Scheduler / Job Queue
**Frequency**: Medium (2025, 2026)
- Submit jobs with priority
- Execute jobs based on priority and submission time
- Support recurring jobs
- Handle job failures and retries
- Monitor job status

### 9. Design an Inventory Management System
**Frequency**: Medium (2024, 2025)
- Product and warehouse management
- Stock tracking (add, remove, transfer)
- Low stock alerts
- Multi-warehouse support
- Concurrency handling for simultaneous orders

### 10. Design a Logging Framework
**Frequency**: Medium (2024, 2025)
- Multiple log levels (DEBUG, INFO, WARN, ERROR)
- Multiple output targets (console, file, remote)
- Configurable formatters
- Thread-safe logging
- Log rotation and archival

### 11. Design a Rate Limiter
**Frequency**: Medium-High (2025, 2026)
- Token bucket / Sliding window algorithms
- Per-user and per-API rate limiting
- Distributed rate limiting
- Configurable limits
- Grace period handling

### 12. Design a Cache System (LRU/LFU)
**Frequency**: High (2024, 2025)
- LRU eviction policy
- Thread-safe operations
- TTL (Time-to-Live) support
- Multiple eviction strategies
- Size-based eviction

---

## Design Patterns Frequently Tested

| Pattern | Example Context |
|---------|----------------|
| Strategy | Payment methods, Sorting algorithms |
| Observer | Notification system, Event handling |
| Factory | Vehicle creation, Payment processor |
| Singleton | Logger, Configuration manager |
| Builder | Complex object construction (Order) |
| Decorator | Adding features to base objects |
| Command | Undo/Redo operations |
| State | Order status, Elevator state |

---

## Key Expectations in Amazon LLD Rounds

1. **Working code expected** - Not just class diagrams
2. **SOLID principles** - Must demonstrate understanding
3. **Extensibility** - Design should be easy to extend
4. **Design Patterns** - Apply relevant patterns naturally
5. **Edge Cases** - Handle concurrency, null cases, boundary conditions
6. **Clean Code** - Proper naming, modular structure
7. **Explain trade-offs** - Why you chose a particular approach
