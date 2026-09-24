# Software Requirements Specification
Debt collection system 

## 1. Modules
- 1.1 Case Management
- 1.2 Data ingestion
- 1.3 Financial Engine
- 1.4 Payments & Allocation
- 1.5 Billings & Invoices
- 1.6 Dialer Emulator
- 1.7 Connection Channels

### 1.1 Case Management
- adding cases, debtors
- assigning case to negotiator
- managing and viewing case
- trakcing case audit and log
- adding notes to case

### 1.2 Data ingestion
- process batch files (excel)
- adds cases, debtors, payments to the system

### 1.3 Financial Engine
- interest calculation

### 1.4 Payments & Allocation
- payments bookings

### 1.5 Billings
- Clients
- Generate invoices
- Contracts
- Provisions

### 1.6 Dialer Emulator
Simulates outbound call center workflows, call distribution, and audio recordings
- Campaign Dispatcher
- Agent state
#### Technology
- Angular 
- WebSockets

### 1.7 Connection channels
- sending emails
- creating templates