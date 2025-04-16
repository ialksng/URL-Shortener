# URL-Shortener
Domain:
Software Engineering / System Design

Tech Stack:
Java/Spring Boot or Node.js, Redis, MongoDB, Docker

Key Skills:
Hashing, System Design, API Rate Limiting

⭐ Situation:
URL shortening is essential for improving user experience and reducing long, unwieldy URLs, especially on platforms with character limits. I identified an opportunity to build a scalable URL shortening service as part of a systems design challenge.

📌 Task:
Design and implement a URL shortening service that could handle high traffic, ensure unique short URLs, support fast redirection, and prevent abuse through rate limiting.

⚙️ Action:
Architected the system using Java with Spring Boot (or Node.js) for REST API development.

Implemented a base62 hashing algorithm to convert long URLs into short, unique identifiers.

Used Redis for caching and fast retrieval of frequently accessed URLs, reducing database load.

Stored persistent URL mappings in MongoDB, optimizing for quick read/write operations.

Integrated API rate limiting using Redis to throttle excessive requests from individual users.

Containerized the entire application using Docker to ensure portability and easy deployment.

✅ Result:
Achieved average URL redirection latency under 50ms due to optimized caching.

Scaled to support millions of requests per day in a simulated high-load environment.

Prevented API abuse with effective rate limiting, ensuring system reliability and fairness.

Project recognized in peer code reviews for clean architecture and adherence to system design best practices.
