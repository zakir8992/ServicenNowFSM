## 📌 ServiceNow FSM – Work Order Journey

This PPT outlines the out-of-the-box (OOB) capabilities and user journey for managing Work Orders in the ServiceNow Field Service Management (FSM) module.

### 🔧 Work Order Initiation
- Work Orders are created directly from Incidents via the **"Create Work Order"** option.
- Core incident data is automatically inherited by the Work Order record.

### 🧾 Work Order Form Overview
- Captures source incident, assignment group, schedule windows, and task status.
- Supports lifecycle tracking across various user roles.

### 🚦 Lifecycle Management
- Both Work Orders (WO) and Work Order Tasks (WOT) progress through defined states.
- Roles such as **Dispatcher** and **Field Agent** handle state transitions.

### 👨‍💼 Dispatcher Responsibilities
- Assigns tasks based on **skills** and **location**.
- Defines dispatch groups and schedules using:
  - Window Start / End
  - Scheduled Start & Travel
  - Estimated End Time

### 🧑‍🔧 Field Agent Workflow
- Accepts/rejects tasks (OOB rejection reasons provided).
- Starts travel and work; durations are automatically captured.
- Completes tasks using:
  - **Close Complete** – logs summary and actual time.
  - **Close Incomplete** – optionally triggers follow-up tasks.

### 💰 Incidentals (Optional OOB Feature)
- Allows agents to log **travel-related expenses** via a related list.



