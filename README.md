# Distributed Systems Architecture

Coursework and assignments exploring how distributed applications communicate, scale, and fail—concepts that map closely to **production support** and reliability.

**Tech Stack:** Java • Networking • Concurrency • Fault Tolerance

## What this repository demonstrates
- Understanding **distributed failure modes** (latency, partial failure, timeouts)
- Reasoning about **concurrency**, coordination, and consistency
- Debugging mindset for multi-component systems (client/server patterns)

### Project Highlights for Production Support:
* **System Reliability:** Implemented mechanisms to handle network timeouts, retries, and node failures, ensuring system stability under stress.
* **Concurrency Control:** Managed multi-threaded processes and race conditions, mirroring real-world application server environments.
* **Client-Server Communication:** Built robust message-passing protocols essential for troubleshooting connectivity between distributed services.

## Topics covered (typical)
- Networking fundamentals, RPC/message passing
- Concurrency and synchronization concepts
- Replication/consistency concepts (event ordering, tradeoffs)
- Fault tolerance basics (retries, backoff, idempotency—conceptually)

## Why it matters for Production Support
Production incidents are often caused by distributed behavior. This work reflects how I approach root cause analysis in multi-service environments.
