# Backend + DSA Interview Preparation (High ROI Plan)

---

## 1. Coding Interviews (DSA) — High ROI Sources

### Core Problem Sets

> Focus here. Avoid random grinding.

- **LeetCode** — https://leetcode.com/problemset/  
  Use for implementation depth and pattern recognition.

- **NeetCode 150** — https://neetcode.io/practice  
  150 problems covering all interview patterns. Treat this as your baseline.

- **Striver's SDE Sheet** — https://takeuforward.org/interviews/strivers-sde-sheet-top-coding-interview-problems/  
  More exhaustive than NeetCode; ideal for revision cycles.

- **GeeksforGeeks DSA Sheet** — https://www.geeksforgeeks.org/dsa-sheet-by-love-babbar/  
  Use as a coverage checklist, not as primary practice.

---

### Topic-wise Deep Dives (Must-Read Explanations)

- **CP-Algorithms** — https://cp-algorithms.com/  
  Clean, math-backed explanations for graphs, DP, number theory.

- **GeeksforGeeks (DSA Section)** — https://www.geeksforgeeks.org/data-structures/  
  Use for definitions, edge cases, and quick revision.

---

## 2. Backend Engineering Interviews (Your Differentiator)

Most candidates stop at DSA. You shouldn't.

### Core Backend / System Design Learning

- **System Design Primer** — https://github.com/donnemartin/system-design-primer  
  Covers scalability, load balancing, caching, and database design.

- **High Scalability** — http://highscalability.com/  
  Real-world system breakdowns (Netflix, Uber, etc.).

---

### Spring Backend (Interview + Practical Depth)

- **Spring Official Documentation** — https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/
- **Baeldung** — https://www.baeldung.com/spring-boot

#### Focus Topics for Interviews

- Dependency Injection internals
- REST API design (status codes, idempotency)
- JPA performance (lazy loading, N+1 problem)
- Transaction management
- Spring Security fundamentals

---

## 3. Most Asked Coding Patterns

Don't memorize questions. **Learn patterns.**

### Core Patterns to Master

- Arrays / Hashing
- Two Pointers / Sliding Window
- Stack / Monotonic Stack
- Binary Search (all variations)
- Trees (DFS, BFS)
- Graphs (BFS, DFS, shortest path)
- Dynamic Programming (core patterns)

### Recommended Sources

- NeetCode → Pattern mapping
- CP-Algorithms → Theory backing

---

## 4. Real Interview Practice (Simulation Layer)

- **InterviewBit** — https://www.interviewbit.com/
- **Pramp** — https://www.pramp.com/
- **Codeforces** — https://codeforces.com/  
  Builds problem-solving speed and pressure handling.

---

## 5. Backend Project Proof (Shortlisting Factor)

You need **2–3 serious projects**, not multiple CRUD clones.

### Minimum Viable "Hireable Backend" Projects

#### 1. Auth Service
- JWT login/signup
- Role-based access
- Refresh tokens

#### 2. Scalable REST API
- Pagination
- Filtering
- Proper error handling
- Logging + monitoring

#### 3. Microservice-lite System
- Two services (User + Orders)
- Inter-service communication (REST or Kafka)
- Basic deployment

---

## 6. Execution Plan (Brutal but Realistic)

### Phase 1 (0–2 Months)
- Complete NeetCode 150
- Build 1 backend project (REST + DB)

### Phase 2 (2–4 Months)
- Solve selected Striver Sheet problems
- Add authentication (JWT)
- Start Codeforces (2–3 contests/week)

### Phase 3 (4–6 Months)
- Complete System Design Primer
- Build microservices project
- Start mock interviews

---
---

# Off-Campus Fintech Companies Preparation Roadmap

## Goal

Prepare for off-campus Software Development Engineer roles in fintech companies such as:

- Razorpay
- PhonePe
- Juspay
- CRED
- Groww
- Paytm
- Navi

> The objective is not just to become good at generic DSA. Fintech companies care about **backend correctness, transaction safety, scalable APIs, concurrency, retries, idempotency, reconciliation, and clean system design.**

---

## 1. Reality Check

There is no genuinely "easy to crack and high-paying" fintech company. These companies pay well because they work on money movement, payments, lending, investments, wallets, UPI, settlements, and financial infrastructure.

**The realistic strategy is:**

Build strong Java DSA + backend fundamentals + one fintech-grade project.

This makes you competitive for off-campus roles where most candidates only have basic DSA and generic clone projects.

---

## 2. Target Companies by Difficulty

| Company  | Crack Difficulty  | Main Focus Areas                                    |
|----------|-------------------|-----------------------------------------------------|
| Paytm    | Medium            | Java/Python, SQL, backend APIs, payments basics     |
| Navi     | Medium to Hard    | Java, Spring Boot, backend design, ownership        |
| Groww    | Hard              | DSA, backend, SQL, finance-domain thinking          |
| Razorpay | Hard              | Payments, APIs, idempotency, distributed systems    |
| PhonePe  | Hard              | Java, concurrency, OOP, scalable backend            |
| CRED     | Hard to Very Hard | Architecture, clean design, product-quality backend |
| Juspay   | Very Hard         | Graphs, DP, payment routing, problem-solving depth  |

**Recommended application order:**

1. Paytm
2. Navi
3. Groww
4. Razorpay
5. PhonePe
6. CRED
7. Juspay

> Paytm and Navi are better entry points. Juspay can be brutal in online assessments, especially graph-heavy rounds.

---

## 3. Ideal Tech Stack

Use one focused backend stack instead of jumping across too many technologies.

### Primary Stack

| Layer             | Technology                   |
|-------------------|------------------------------|
| Language          | Java                         |
| Backend Framework | Spring Boot                  |
| Database          | PostgreSQL                   |
| Cache             | Redis                        |
| Message Queue     | Kafka or RabbitMQ            |
| Testing           | JUnit and Mockito            |
| DevOps            | Docker and GitHub Actions    |
| Documentation     | Swagger / OpenAPI            |
| Deployment        | Render, Railway, AWS, or VPS |

### Why This Stack?

Fintech systems need:

- Correct API behavior
- Reliable database transactions
- Duplicate request protection
- Async processing
- Auditability
- Retry-safe workflows
- Clean service boundaries

**Java + Spring Boot + PostgreSQL** is highly relevant for this domain.

---

## 4. DSA Preparation Roadmap

Minimum target: **200 to 220 quality problems.**

Do not solve randomly. Solve by patterns.

### Must-Master Topics

| Topic                      | Required Level   |
|----------------------------|------------------|
| Arrays and Hashing         | Strong           |
| Two Pointers               | Strong           |
| Sliding Window             | Strong           |
| Binary Search              | Strong           |
| Stack and Monotonic Stack  | Strong           |
| Linked List                | Medium           |
| Trees                      | Strong           |
| Graphs                     | Very Strong      |
| Heaps / Priority Queue     | Strong           |
| Dynamic Programming        | Medium to Strong |
| Greedy                     | Medium           |
| Bit Manipulation           | Basic to Medium  |
| Recursion and Backtracking | Medium           |

---

## 5. High-Priority DSA Questions

### Arrays and Hashing

- Two Sum
- Group Anagrams
- Top K Frequent Elements
- Product of Array Except Self
- Subarray Sum Equals K
- Longest Consecutive Sequence
- Contains Duplicate
- Valid Anagram

### Two Pointers and Sliding Window

- 3Sum
- Container With Most Water
- Longest Substring Without Repeating Characters
- Minimum Window Substring
- Permutation in String
- Best Time to Buy and Sell Stock
- Trapping Rain Water

### Binary Search

- Binary Search
- Search in Rotated Sorted Array
- Find Minimum in Rotated Sorted Array
- Koko Eating Bananas
- Capacity to Ship Packages
- Median of Two Sorted Arrays
- Search a 2D Matrix

### Stack

- Valid Parentheses
- Min Stack
- Daily Temperatures
- Next Greater Element
- Largest Rectangle in Histogram
- Evaluate Reverse Polish Notation

### Trees

- Maximum Depth of Binary Tree
- Diameter of Binary Tree
- Binary Tree Level Order Traversal
- Lowest Common Ancestor
- Validate Binary Search Tree
- Serialize and Deserialize Binary Tree
- Kth Smallest Element in BST

### Graphs

- Number of Islands
- Rotten Oranges
- Clone Graph
- Course Schedule
- Network Delay Time
- Cheapest Flights Within K Stops
- Dijkstra Algorithm
- Topological Sort
- Cycle Detection
- Disjoint Set Union
- Minimum Spanning Tree

### Dynamic Programming

- Climbing Stairs
- House Robber
- Coin Change
- Longest Increasing Subsequence
- Minimum Cost For Tickets
- Unique Paths
- Partition Equal Subset Sum
- Longest Common Subsequence

---

## 6. Backend Topics You Cannot Skip

Fintech interviews are not only about DSA. You must understand backend correctness.

| Concept          | Why It Matters                                                |
|------------------|---------------------------------------------------------------|
| REST APIs        | Payments and financial services expose APIs                   |
| SQL Transactions | Money movement must be atomic                                 |
| ACID Properties  | Prevents corrupted financial state                            |
| Isolation Levels | Avoids dirty reads, phantom reads, double-spend issues        |
| Idempotency Keys | Prevents duplicate payments or refunds                        |
| Retry Logic      | Payment systems often fail partially                          |
| Webhooks         | Payment status updates depend on callbacks                    |
| Message Queues   | Used for async settlements, notifications, reconciliation     |
| Redis Locks      | Useful for basic distributed coordination                     |
| Rate Limiting    | Protects APIs from abuse                                      |
| Audit Logs       | Financial systems need traceability                           |
| Reconciliation   | Ensures gateway, bank, and internal records match             |
| State Machines   | Payment lifecycle must be explicit                            |
| Observability    | Logs, metrics, alerts, and tracing are mandatory              |

---

## 7. Fintech Project to Build

Build **one strong project** instead of five weak projects.

### Project: PayFlow — Mini Payment Gateway and Ledger System

This project should simulate a real payment infrastructure backend.

---

### Core Modules

#### 1. User and Merchant Service

- User registration
- Merchant registration
- API key generation
- Merchant webhook URL registration

#### 2. Wallet / Account Service

- User wallet
- Merchant account
- Balance table
- Ledger table

#### 3. Payment Service

- Create payment
- Authorize payment
- Capture payment
- Fail payment
- Refund payment

#### 4. Idempotency System

Every payment request should have an `idempotencyKey`.

- Same key should not create duplicate payments.
- If the first request succeeded, repeated requests should return the same response.
- If the first request failed midway, system behavior should be predictable.

#### 5. Transaction Ledger

Use a **double-entry ledger**. For every successful payment:

| Entry Type | Account          | Amount |
|------------|------------------|--------|
| Debit      | User Wallet      | 500    |
| Credit     | Merchant Account | 500    |

- Debit user account
- Credit merchant account
- Store immutable transaction entries

#### 6. Refund System

- Full refund
- Partial refund
- Refund status tracking
- Duplicate refund prevention

#### 7. Webhook System

- Merchant webhook endpoint
- Retry failed webhook delivery
- Exponential backoff
- Webhook delivery logs

#### 8. Reconciliation Job

Daily job that checks payment, ledger, refund, and settlement tables. Identifies mismatches and generates a reconciliation report.

#### 9. Fraud Rules

- Block too many payments in 1 minute
- Flag unusually high amount
- Flag repeated failed attempts
- Flag suspicious merchant activity

#### 10. Admin APIs

- View failed payments
- View pending refunds
- View reconciliation mismatches
- View settlement reports
- View suspicious transactions

---

## 8. Suggested Database Tables

### `users`
| Column     | Type      |
|------------|-----------|
| id         | UUID / PK |
| name       | VARCHAR   |
| email      | VARCHAR   |
| created_at | TIMESTAMP |

### `merchants`
| Column        | Type      |
|---------------|-----------|
| id            | UUID / PK |
| business_name | VARCHAR   |
| email         | VARCHAR   |
| api_key       | VARCHAR   |
| webhook_url   | VARCHAR   |
| created_at    | TIMESTAMP |

### `accounts`
| Column     | Type      |
|------------|-----------|
| id         | UUID / PK |
| owner_id   | UUID / FK |
| owner_type | VARCHAR   |
| balance    | DECIMAL   |
| created_at | TIMESTAMP |
| updated_at | TIMESTAMP |

### `payments`
| Column          | Type      |
|-----------------|-----------|
| id              | UUID / PK |
| payment_id      | VARCHAR   |
| user_id         | UUID / FK |
| merchant_id     | UUID / FK |
| amount          | DECIMAL   |
| currency        | VARCHAR   |
| status          | VARCHAR   |
| idempotency_key | VARCHAR   |
| created_at      | TIMESTAMP |
| updated_at      | TIMESTAMP |

### `ledger_entries`
| Column         | Type      |
|----------------|-----------|
| id             | UUID / PK |
| transaction_id | UUID / FK |
| account_id     | UUID / FK |
| entry_type     | VARCHAR   |
| amount         | DECIMAL   |
| created_at     | TIMESTAMP |

### `refunds`
| Column          | Type      |
|-----------------|-----------|
| id              | UUID / PK |
| refund_id       | VARCHAR   |
| payment_id      | UUID / FK |
| amount          | DECIMAL   |
| status          | VARCHAR   |
| idempotency_key | VARCHAR   |
| created_at      | TIMESTAMP |
| updated_at      | TIMESTAMP |

### `webhook_events`
| Column      | Type      |
|-------------|-----------|
| id          | UUID / PK |
| merchant_id | UUID / FK |
| event_type  | VARCHAR   |
| payload     | JSONB     |
| status      | VARCHAR   |
| retry_count | INT       |
| created_at  | TIMESTAMP |
| updated_at  | TIMESTAMP |

---

## 9. Payment Status Machine

```
CREATED
   |
AUTHORIZED
   |
CAPTURED
   |
SETTLED
```

**Failure paths:**

```
CREATED       --> FAILED
AUTHORIZED    --> FAILED
CAPTURED      --> REFUND_INITIATED --> REFUNDED
```

**Important rule:** Never allow random status transitions.

| From State       | Allowed Transitions       |
|------------------|---------------------------|
| CREATED          | AUTHORIZED, FAILED        |
| AUTHORIZED       | CAPTURED, FAILED          |
| CAPTURED         | SETTLED, REFUND_INITIATED |
| REFUND_INITIATED | REFUNDED                  |
| SETTLED          | — (terminal)              |
| FAILED           | — (terminal)              |

---

## 10. Resume Bullets for This Project

> Built a payment-gateway simulation backend using Java, Spring Boot, PostgreSQL, Redis, and Kafka, supporting idempotent payment creation, double-entry ledger, refunds, webhook retries, reconciliation jobs, fraud-rule checks, and Dockerized deployment.

> Designed a fintech-grade backend system with transaction-safe payment processing, immutable ledger entries, retry-safe webhooks, Redis-based rate limiting, and scheduled reconciliation workflows.

---

## 11. Company-Specific Preparation

### Razorpay
**Focus:** Payment APIs, Idempotency, Webhooks, SQL transactions, Refunds, Reconciliation, DSA medium-hard, Backend system design  
**Project angle:** Payment gateway simulator, gateway routing, refund handling, settlement reports

### PhonePe
**Focus:** Java, OOP, Multithreading, Concurrency, LLD, API design, High-scale backend  
**Project angle:** UPI transaction state machine, wallet ledger, transaction history, failure-safe retries

### Juspay
**Focus:** Graphs, Dynamic programming, Payment routing, Problem-solving speed, Functional-style thinking  
**Project angle:** Payment router that chooses the best gateway based on success rate, latency, and failure history

### CRED
**Focus:** Backend architecture, LLD, Clean code, Product-quality engineering, Domain modeling  
**Project angle:** Order and payment lifecycle system, audit logs, state machine, transaction consistency

### Groww
**Focus:** DSA, SQL, OS, Threads, Backend design, Investment/trading basics  
**Project angle:** Stock order system, portfolio tracker, transaction history, mutual fund order simulation

### Paytm
**Focus:** Java or Python, SQL, Payment APIs, Wallet systems, Notifications, High-volume systems  
**Project angle:** Wallet and QR payment simulator

### Navi
**Focus:** Java, Spring Boot, Lending workflows, UPI, Insurance, Ownership, Fast backend execution  
**Project angle:** Loan approval and repayment ledger system

---

## 12. 90-Day Execution Plan

### Days 1–30: DSA Foundation

**Daily work:** 2 LeetCode problems · 30 min Java revision · 30 min CS fundamentals

**Focus topics:** Arrays, Hashing, Strings, Two Pointers, Sliding Window, Binary Search, Stack, Queue

**Expected output:**
- 60 solved problems
- Pattern-wise notes
- Java templates ready

---

### Days 31–60: Advanced DSA and CS Core

**Daily work:** 2–3 problems · 1 CS topic · 1 SQL query set

**Focus topics:** Trees, Graphs, DP, Heaps, Greedy, OS, DBMS, CN, SQL joins/subqueries/indexes

**Expected output:**
- 140–160 total solved problems
- Strong graph basics
- SQL confidence
- CS notes ready for interviews

---

### Days 61–90: Project and Interview Simulation

**Daily work:** 1 DSA revision · 1 backend module · 1 interview-style explanation

**Build:** Payment creation · Idempotency · Ledger · Refunds · Webhooks · Reconciliation · Redis rate limiting · Docker setup · README · API documentation

**Expected output:**
- 220+ DSA problems
- 1 fintech-grade project
- Resume-ready backend bullet points
- Mock interview answers

---

## 13. Weekly Schedule

| Day       | Focus                     |
|-----------|---------------------------|
| Monday    | Arrays + Hashing + Java   |
| Tuesday   | Sliding Window + SQL      |
| Wednesday | Binary Search + DBMS      |
| Thursday  | Stack/Queue + OS          |
| Friday    | Trees + CN                |
| Saturday  | Graphs + Project          |
| Sunday    | DP + Project + Revision   |

**Daily minimum:** 90 min DSA · 45 min CS/SQL · 45 min backend project = **3 hours total**

---

## 14. Off-Campus Application Strategy

**Apply through:** Company career pages · LinkedIn Jobs · Instahyre · Wellfound · Cutshort · Unstop · HackerEarth · Referrals · GitHub networking

**Weekly targets:**
- 20 normal applications
- 10 referral attempts
- 2 hiring challenges
- 1 resume/project improvement

---

## 15. GitHub Strategy

Your repository should include:

- Clean README
- Architecture diagram
- API documentation
- Setup commands
- Docker Compose file
- Database schema
- Postman collection
- Screenshots
- Test cases
- Known limitations
- Future improvements

### Minimum Repository Structure

```
payflow/
├── src/
├── docs/
│   ├── architecture.md
│   ├── api-docs.md
│   └── database-schema.md
├── docker-compose.yml
├── README.md
└── postman_collection.json
```

---

## 16. Interview Explanation Template

When asked about your project, explain in this order:

1. Problem statement
2. System requirements
3. Tech stack
4. Database design
5. Payment lifecycle
6. Idempotency handling
7. Ledger correctness
8. Failure handling
9. Webhook retry logic
10. Reconciliation job
11. What you would improve next

**Sample answer:**

> I built PayFlow as a mini payment-gateway backend. The main engineering challenge was to avoid duplicate financial operations during retries. I used idempotency keys, database transactions, an immutable double-entry ledger, and explicit payment states. I also added webhook retries and reconciliation jobs to simulate real payment infrastructure behavior.

---

## 17. Final Execution Checklist

- [ ] 200+ DSA problems solved
- [ ] Java DSA templates ready
- [ ] SQL joins and indexing revised
- [ ] OS basics revised
- [ ] DBMS transactions revised
- [ ] CN basics revised
- [ ] Spring Boot project completed
- [ ] PostgreSQL integrated
- [ ] Redis integrated
- [ ] Kafka or RabbitMQ integrated
- [ ] Docker setup working
- [ ] GitHub README polished
- [ ] Resume updated
- [ ] LinkedIn updated
- [ ] 3 mock interviews done
- [ ] 50+ applications sent
- [ ] 20+ referral messages sent

---

## 18. Final Verdict

Your fintech off-campus preparation should be built around this formula:

```
Java DSA
+ Spring Boot Backend
+ PostgreSQL
+ Redis
+ Kafka
+ Fintech Project
+ CS Fundamentals
+ Strong Resume Positioning
```

The strongest project for your profile is:

> **PayFlow — Mini Payment Gateway and Ledger System**

If executed properly, this project can position you better than generic MERN-clone candidates and make you relevant for fintech backend roles.
