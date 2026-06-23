# Google - Low Level Design Interview Questions (2024-2026)

Real LLD questions asked in Google L3, L4, L5 interview rounds.

**Note**: Google focuses more on System Design (HLD) than pure LLD/Machine Coding for senior roles. However, for L3-L4, object-oriented design questions are asked.

---

## Frequently Asked LLD Problems

### 1. Design a File System
**Frequency**: High (2024, 2025)
- In-memory file system with directory hierarchy
- Support mkdir, ls, addContent, readContent
- Path resolution and traversal
- File permissions and metadata
- Search functionality

### 2. Design a Search Autocomplete System
**Frequency**: High (2024, 2025)
- Trie-based implementation
- Top-K suggestions by frequency
- Support for real-time updates
- Handle deletions and updates
- Ranking based on recency and frequency

### 3. Design a Rate Limiter
**Frequency**: High (2025, 2026)
- Token bucket algorithm
- Sliding window log/counter
- Per-user and per-API limits
- Distributed rate limiting
- Configurable time windows

### 4. Design a Key-Value Store
**Frequency**: Medium-High (2024, 2025)
- Put, Get, Delete operations
- TTL (Time-to-Live) support
- Snapshotting capability
- Versioned values
- Thread-safe operations

### 5. Design a Task Scheduler
**Frequency**: Medium (2025, 2026)
- Priority-based execution
- Cron-like recurring tasks
- Dependency management between tasks
- Retry with backoff
- Concurrent task execution with limits

### 6. Design a Spreadsheet (Google Sheets)
**Frequency**: Medium-High (2024, 2025)
- Cell value management (raw values and formulas)
- Formula evaluation with dependencies
- Circular dependency detection
- Cell formatting
- Range operations (SUM, AVG)

### 7. Design a URL Shortener
**Frequency**: Medium (2024, 2025)
- Short URL generation (base62 encoding)
- Redirect handling
- Analytics (click count, geographic data)
- Custom aliases
- Expiration support

### 8. Design a Pub/Sub Messaging System
**Frequency**: Medium (2025, 2026)
- Topic creation and management
- Publish messages to topics
- Subscribe/unsubscribe
- Message ordering guarantees
- At-least-once delivery

### 9. Design a Connection Pool
**Frequency**: Medium (2024, 2025)
- Pool initialization with configurable size
- Acquire and release connections
- Health checking
- Timeout handling
- Max wait time for acquiring

### 10. Design a Thread Pool
**Frequency**: Medium (2025)
- Fixed and dynamic pool sizing
- Task queue management
- Graceful shutdown
- Thread reuse
- Rejection policies when pool is full

### 11. Design an LRU Cache with TTL
**Frequency**: High (2024, 2025)
- LRU eviction policy
- TTL-based expiration
- O(1) get and put
- Thread-safe implementation
- Capacity management

### 12. Design Google Maps (Routing Component)
**Frequency**: Medium (2025, 2026)
- Graph representation of road network
- Shortest path (Dijkstra / A*)
- Multiple route suggestions
- Traffic-aware routing
- ETA calculation

---

## Design Patterns Emphasized at Google

| Pattern | Context |
|---------|---------|
| Strategy | Algorithm selection (routing, sorting) |
| Observer | Event-driven updates |
| Iterator | Custom collection traversal |
| Composite | File system hierarchy |
| Proxy | Caching, lazy loading |
| Builder | Complex query construction |
| Flyweight | Shared immutable objects |

---

## Key Expectations

1. **Clean API design** - Method signatures should be intuitive
2. **Extensibility** - Design for change
3. **Concurrency** - Thread safety is critical
4. **Testing** - Discuss how you'd unit test
5. **Complexity analysis** - Time and space for each operation
6. **Trade-offs** - Multiple approaches with pros/cons
7. **Production readiness** - Error handling, edge cases, monitoring
