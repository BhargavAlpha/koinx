# Microsoft - Low Level Design Interview Questions (2024-2026)

Real LLD/Machine Coding questions asked in Microsoft SDE interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design a Parking Lot System
**Frequency**: Very High (2024, 2025, 2026)
- Car sizes: S, M, L with limited spots (e.g., 200 S, 100 M, 50 L)
- If exact size unavailable, assign next highest size
- Price sheet based on parking lot size per hour
- Calculate charge at exit based on actual duration
- Working code expected

### 2. Design a Movie Ticket Booking System (BookMyShow)
**Frequency**: High (2024, 2025)
- Theater and screen management
- Show scheduling
- Seat selection with concurrency handling
- Booking and cancellation
- Payment integration
- Notification on booking confirmation

### 3. Design Multiplayer Tic-Tac-Toe
**Frequency**: High (2025, 2026)
- Support N x N grid
- Multiple players (2+)
- Turn management
- Win detection algorithm
- Game state management
- Undo move functionality

### 4. Design a Ride-Sharing Service (Uber)
**Frequency**: High (2024, 2025)
- Driver and rider management
- Trip lifecycle (request -> match -> ride -> complete)
- Fare calculation with distance and time
- Rating system for both driver and rider
- Surge pricing logic

### 5. Design an Elevator System
**Frequency**: Medium-High (2024, 2025)
- Multiple elevators with scheduling
- Request handling (internal and external)
- Direction optimization (SCAN algorithm)
- Weight capacity management
- Emergency handling

### 6. Design a Hotel Booking System
**Frequency**: Medium (2025, 2026)
- Room types and availability management
- Booking with date range
- Check-in / Check-out
- Pricing with seasonal variations
- Cancellation policies and refund

### 7. Design a File System
**Frequency**: Medium (2024, 2025)
- Directory and file hierarchy
- CRUD operations on files/directories
- Path resolution
- Permissions management
- Search functionality

### 8. Design a Chat Application
**Frequency**: Medium (2025, 2026)
- One-to-one and group messaging
- Message delivery status (sent, delivered, read)
- Online/offline status
- Message history
- Media sharing

### 9. Design a Task Management System (Trello/Jira)
**Frequency**: Medium (2024, 2025)
- Board, List, Card hierarchy
- Drag and drop (state transitions)
- Assignment and due dates
- Comments and activity log
- Label and filter system

### 10. Design a Snake and Ladder Game
**Frequency**: Medium (2024, 2025)
- Board with configurable snakes and ladders
- Multiple players
- Dice rolling
- Win condition
- Turn management

---

## Non-Functional Requirements Tested

Microsoft explicitly asks candidates to discuss:
- **Scalability**: How the design handles increased load
- **Performance**: Response time considerations
- **Concurrency**: Thread safety and race conditions
- **Extensibility**: How to add new features without breaking existing ones

---

## Design Patterns Emphasized at Microsoft

| Pattern | Common Context |
|---------|---------------|
| Strategy | Pricing algorithms, Sorting |
| Observer | Real-time updates, Notifications |
| Factory | Object creation (vehicles, rooms) |
| Singleton | Configuration, Connection pools |
| State | Game state, Order lifecycle |
| Command | Undo/Redo, Action history |
| Adapter | Third-party integrations |
| Template Method | Common workflows with variations |

---

## Key Expectations

1. **Working code is mandatory** - Must compile and run
2. **Discuss non-functional requirements** proactively
3. **Draw class diagrams** before coding (use excalidraw in virtual)
4. **SOLID principles** - Interviewers specifically ask about these
5. **Design Patterns** - Know when and why to apply
6. **Extensibility** - "What if we add feature X?" follow-ups are common
7. **Testing** - Mention how you'd test your design
