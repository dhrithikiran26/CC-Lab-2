# CC-Lab-2
Monolithic Architecture Lab: Performance &amp; Reliability. Explores single points of failure in FastAPI, load testing with Locust, and optimizing Python logic from O(n^2) to O(n) to improve system throughput and latency.

**Objective:** Demonstrating how a single bug (like the 1/0 crash) can take down an entire monolithic application.

**Optimization:** Improving the /events and /my-events routes by removing inefficient nested loops and simplifying database access.

**Tools Used:** FastAPI, SQLite, and Locust for load simulation.
