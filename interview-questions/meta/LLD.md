# Meta (Facebook) - Low Level Design Interview Questions (2024-2026)

Real LLD questions asked in Meta E3, E4, E5 interview rounds.

**Note**: Meta focuses more heavily on coding (DSA) and system design (HLD) than pure LLD. However, design-oriented coding problems and some OOD questions are asked.

---

## Frequently Asked LLD / Design Coding Problems

### 1. Design a Social Media Feed
**Frequency**: High (2024, 2025)
- Post creation (text, image, video)
- News Feed generation algorithm
- Like, comment, share functionality
- Follow/unfollow mechanism
- Feed ranking and sorting
- Pagination

### 2. Design a Messenger / Chat System
**Frequency**: High (2024, 2025, 2026)
- One-to-one messaging
- Group chats
- Message status (sent, delivered, read)
- Online/offline indicator
- Media sharing
- Message threading

### 3. Design a Notification System
**Frequency**: Medium-High (2024, 2025)
- Push, Email, In-app notifications
- Notification preferences
- Priority-based delivery
- Rate limiting per user
- Batch notifications
- Read/unread status

### 4. Design a Photo Sharing Application (Instagram)
**Frequency**: Medium-High (2025, 2026)
- Upload and store photos
- Filters and editing
- Hashtags and captions
- Explore/Discovery feed
- Stories (24-hour content)
- User interactions (like, comment, save)

### 5. Design an Event System / Pub-Sub
**Frequency**: Medium (2024, 2025)
- Publishers and subscribers
- Topic management
- Event filtering
- Guaranteed delivery
- Ordering guarantees
- Dead letter queue

### 6. Design a Rate Limiter
**Frequency**: Medium-High (2025, 2026)
- Token bucket / Sliding window
- Per-user and per-endpoint limits
- Distributed implementation
- Configurable windows
- Burst handling

### 7. Design a URL Shortener
**Frequency**: Medium (2024, 2025)
- Generate short URLs
- Redirect to original URL
- Click analytics
- Custom aliases
- Expiration support
- Collision handling

### 8. Design a Content Moderation System
**Frequency**: Medium (2025, 2026)
- Content classification (safe, unsafe, review)
- Multiple content types (text, image, video)
- Rules engine
- Human review queue
- Appeal process
- Audit trail

### 9. Design a Friend Recommendation System
**Frequency**: Medium (2024, 2025)
- Mutual friends calculation
- Graph-based recommendations
- Scoring and ranking
- Filter already-connected users
- Privacy controls
- Real-time updates

### 10. Design a Search Typeahead
**Frequency**: Medium (2025)
- Prefix-based suggestions
- Personalized results
- Trending searches
- Recent searches
- Trie-based implementation
- Ranking by relevance

---

## Design Patterns Common at Meta

| Pattern | Context |
|---------|---------|
| Observer | Feed updates, notifications |
| Strategy | Feed ranking algorithms |
| Factory | Content type creation |
| Decorator | Content enrichment (filters) |
| Command | Action history, undo |
| Chain of Responsibility | Content moderation pipeline |
| Proxy | Lazy loading media |

---

## Key Expectations

1. **Social graph awareness** - Think in terms of connections and relationships
2. **Scale thinking** - Design for billions of users
3. **Speed** - Complete design + code in 35-45 minutes
4. **Communication** - Explain trade-offs clearly
5. **Production quality** - Error handling, edge cases
6. **Privacy considerations** - Data access controls
7. **Real-time aspects** - Immediate feedback loops
