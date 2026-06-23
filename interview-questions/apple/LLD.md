# Apple - Low Level Design Interview Questions (2024-2026)

Real LLD questions asked in Apple ICT2, ICT3, ICT4 interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design an LRU Cache
**Frequency**: Very High (2024, 2025)
- O(1) get and put operations
- Thread-safe implementation
- Configurable capacity
- TTL support (optional)
- Eviction callback

### 2. Design a File System
**Frequency**: High (2024, 2025)
- Hierarchical directory structure
- File/folder CRUD operations
- Path traversal and resolution
- Permissions (read, write, execute)
- Symbolic links support

### 3. Design a Music Player (Apple Music)
**Frequency**: High (2025, 2026)
- Play, pause, skip, previous
- Playlist management (create, add, remove, shuffle)
- Queue management
- Repeat modes (one, all, off)
- Search by song, artist, album
- Recently played history

### 4. Design a Notification System
**Frequency**: Medium-High (2024, 2025)
- Multiple channels (push, email, SMS)
- User preferences and opt-out
- Priority levels
- Delivery scheduling
- Template management
- Retry mechanism

### 5. Design a Photo Library (iCloud Photos)
**Frequency**: Medium (2025, 2026)
- Album management
- Photo metadata (date, location, tags)
- Search by date, location, person
- Favorites and trash
- Storage quota management
- Sync state management

### 6. Design a Task Manager / Reminders App
**Frequency**: Medium (2024, 2025)
- Create, update, delete tasks
- Due dates and reminders
- Priority levels
- Lists/categories
- Recurring tasks
- Subtasks support

### 7. Design a Text Editor
**Frequency**: Medium (2024, 2025)
- Insert, delete, cursor movement
- Undo/redo (Command pattern)
- Copy/paste with clipboard
- Find and replace
- Word wrap
- Character/word/line count

### 8. Design a Contact Book
**Frequency**: Medium (2024, 2025)
- Add, update, delete contacts
- Multiple phone numbers, emails per contact
- Groups/categories
- Search by name, phone, email
- Favorites
- Import/export (vCard)

### 9. Design a Calendar Application
**Frequency**: Medium (2025, 2026)
- Event CRUD with recurrence
- Overlapping event detection
- Reminders/notifications
- Multiple calendars
- Invite attendees
- Timezone handling

### 10. Design an App Store
**Frequency**: Medium (2025)
- App catalog with categories
- Search and discovery
- Download/Install management
- Version management and updates
- Reviews and ratings
- Developer accounts

---

## Apple-Specific Design Emphasis

Apple interviews uniquely focus on:
1. **Memory Efficiency** - Minimize memory footprint
2. **User Experience** - Design should reflect intuitive UX
3. **Privacy** - Data minimization in design
4. **Offline Support** - Graceful degradation without network
5. **Platform Integration** - Awareness of iOS/macOS frameworks

---

## Design Patterns Emphasized at Apple

| Pattern | Context |
|---------|---------|
| Command | Undo/Redo, Action history |
| Observer | UI updates, State changes |
| Strategy | Algorithm interchangeability |
| Delegate | iOS-style callbacks |
| MVC/MVVM | App architecture |
| Factory | Object creation |
| Prototype | Cloning complex objects |
| Memento | State snapshot (undo) |

---

## Key Expectations

1. **Clean, defensive code** - Edge cases handled meticulously
2. **Memory awareness** - Efficient resource usage
3. **API design** - Intuitive method signatures
4. **SOLID principles** - Clean separation of concerns
5. **Testability** - Design should be easily unit-testable
6. **Platform thinking** - Consider iOS/macOS constraints
7. **Concurrency** - Thread-safe designs with GCD/DispatchQueue awareness
