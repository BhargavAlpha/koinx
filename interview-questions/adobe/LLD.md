# Adobe - Low Level Design Interview Questions (2024-2026)

Real LLD/Machine Coding questions asked in Adobe MTS interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design a Collaborative Document Editor (Google Docs)
**Frequency**: Very High (2024, 2025, 2026) - Adobe-specific
- Real-time multi-user editing
- Conflict resolution (OT or CRDT)
- Cursor position management
- Undo/Redo per user
- Version history
- Comments and suggestions
- Delta compression for efficiency

### 2. Design a Social Media Platform
**Frequency**: High (2024, 2025)
- User profiles and relationships
- Post creation (text, image)
- News feed generation
- Like, comment, share
- Follow/unfollow
- Notification system

### 3. Design a File Storage System (Creative Cloud)
**Frequency**: High (2025, 2026) - Adobe-specific
- Upload/download large files
- Version management
- Folder hierarchy
- Sharing with permissions
- Offline sync
- Conflict resolution for concurrent edits

### 4. Design a Parking Lot System
**Frequency**: Medium-High (2024, 2025)
- Multiple levels and spot types
- Vehicle entry/exit
- Spot assignment algorithm
- Pricing and billing
- Capacity management
- Real-time availability

### 5. Design a Text Editor (like Photoshop text tool)
**Frequency**: Medium (2024, 2025) - Adobe-specific
- Insert, delete, move cursor
- Font styling (bold, italic, underline)
- Undo/redo with Command pattern
- Copy/paste clipboard
- Text alignment
- Layer management

### 6. Design a PDF Viewer/Editor
**Frequency**: Medium (2025, 2026) - Adobe-specific
- Page navigation
- Zoom and scroll
- Annotations (highlight, underline, comment)
- Bookmark management
- Form filling
- Signature support

### 7. Design an Image Filter Pipeline
**Frequency**: Medium (2024, 2025) - Adobe-specific
- Apply filters sequentially
- Chain of filters (Pipeline pattern)
- Custom filter creation
- Preview before apply
- Undo filter application
- Batch processing

### 8. Design a Pub/Sub Event System
**Frequency**: Medium (2024, 2025)
- Publishers and subscribers
- Topic-based routing
- Message ordering
- At-least-once delivery
- Subscriber groups
- Dead letter handling

### 9. Design a URL Shortener
**Frequency**: Medium (2024, 2025)
- Short URL generation
- Redirect management
- Analytics (clicks, geographic)
- Custom aliases
- Expiration
- Rate limiting

### 10. Design a Workflow Automation System
**Frequency**: Medium (2025, 2026)
- Define workflow steps
- Conditional branching
- Sequential and parallel execution
- Error handling
- Retry policies
- Audit trail

---

## Adobe-Specific Design Focus

Adobe interviews uniquely emphasize:
1. **Creative Workflows** - Design around creative tools and assets
2. **Real-time Collaboration** - OT/CRDT for concurrent editing
3. **Large Binary Assets** - Handling PSD, AI, PDF files efficiently
4. **Delta Compression** - Efficient sync for large files
5. **Offline Sync** - Work offline, sync when connected
6. **Version History** - Non-destructive editing with rollback

---

## Design Patterns Emphasized at Adobe

| Pattern | Context |
|---------|---------|
| Command | Undo/Redo, Action recording |
| Strategy | Filter algorithms, Rendering |
| Observer | Real-time collaboration updates |
| Chain of Responsibility | Filter pipeline |
| Composite | Layer/Group hierarchy |
| Flyweight | Shared font/style resources |
| Memento | State snapshots |
| Decorator | Feature addition to elements |

---

## Key Expectations

1. **Working code expected** - Clean, production-quality
2. **OOP fundamentals** - Strong class design
3. **Creative domain awareness** - Understand asset handling
4. **Real-time considerations** - Collaboration and sync
5. **Performance** - Handle large files efficiently
6. **Extensibility** - Plugin/extension architecture
7. **Clean separation** - MVC or similar patterns
