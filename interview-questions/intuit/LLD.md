# Intuit - Low Level Design Interview Questions (2024-2026)

Real LLD questions asked in Intuit SDE-1, SDE-2 interview rounds.

---

## Frequently Asked LLD Problems

### 1. Design a Splitwise / Expense Sharing System
**Frequency**: Very High (2024, 2025, 2026) - Intuit domain (financial)
- Add users and groups
- Add expenses (equal, exact, percentage splits)
- Track balances between users
- Simplify debts (minimize transactions)
- Settlement/payment recording
- Expense history and reports

### 2. Design a Banking/Payment System
**Frequency**: High (2024, 2025) - Intuit domain
- Account management (create, close)
- Transaction processing (credit, debit, transfer)
- Balance inquiry
- Transaction history
- Overdraft protection
- Recurring payments
- Multi-currency support

### 3. Design a Tax Calculator (TurboTax-inspired)
**Frequency**: High (2025, 2026) - Intuit domain
- Income types (salary, business, capital gains)
- Deduction categories
- Tax slab/bracket calculation
- Multiple filing statuses
- Tax credits application
- Generate tax summary report
- Strategy pattern for different tax regimes

### 4. Design an Invoice Management System
**Frequency**: Medium-High (2024, 2025) - QuickBooks domain
- Create and send invoices
- Line items with tax calculation
- Payment tracking (partial, full)
- Recurring invoices
- Overdue notifications
- PDF generation
- Multi-currency

### 5. Design a Subscription Management System
**Frequency**: Medium (2025, 2026)
- Plan management (tiers, features)
- Subscribe/upgrade/downgrade/cancel
- Billing cycle management
- Prorated charges
- Trial periods
- Payment method management
- Renewal notifications

### 6. Design a Budget Tracker / Expense Manager
**Frequency**: Medium-High (2024, 2025) - Intuit domain
- Category-wise budget setting
- Expense logging
- Budget vs actual tracking
- Alerts on overspending
- Monthly/weekly/yearly views
- Reports and insights
- Recurring expenses

### 7. Design a Library Management System
**Frequency**: Medium (2024, 2025)
- Book catalog management
- Member management
- Issue/return with due dates
- Fine calculation
- Reservation system
- Search functionality

### 8. Design a Food Delivery System
**Frequency**: Medium (2024, 2025)
- Restaurant and menu management
- Order placement and tracking
- Delivery assignment
- Rating system
- Payment processing
- Estimated delivery time

### 9. Design a Parking Lot System
**Frequency**: Medium (2024, 2025)
- Multiple levels and vehicle types
- Spot assignment
- Pricing calculation
- Entry/exit management
- Capacity tracking

### 10. Design a Notification Service
**Frequency**: Medium (2025, 2026)
- Multiple channels (email, SMS, push)
- Template management
- User preferences
- Rate limiting
- Retry mechanism
- Priority handling

---

## Intuit-Specific Design Focus

Intuit interviews emphasize:
1. **Financial Domain** - Understand money, transactions, taxes
2. **Accuracy** - Financial calculations must be precise (BigDecimal)
3. **Audit Trail** - Every financial action must be traceable
4. **Data Integrity** - Transactions must be atomic
5. **Customer-Centric** - Design for small business owners
6. **Security** - Financial data protection
7. **Scalability** - Handle tax season spikes

---

## Design Patterns Emphasized at Intuit

| Pattern | Context |
|---------|---------|
| Strategy | Tax calculation, Pricing |
| Observer | Balance updates, Notifications |
| Factory | Transaction types, Report generation |
| Builder | Invoice construction, Report building |
| Template Method | Tax filing workflow |
| Command | Transaction processing, Undo |
| Decorator | Adding features to base plans |
| Singleton | Configuration, Tax rules engine |

---

## Key Expectations

1. **Financial accuracy** - Use proper decimal handling
2. **Transaction safety** - ACID properties awareness
3. **Clean architecture** - Layered design (Service/Repository)
4. **Testability** - Unit testable components
5. **Error handling** - Graceful failure, no data loss
6. **Domain knowledge** - Basic understanding of accounting/finance
7. **API design** - RESTful, well-documented endpoints
