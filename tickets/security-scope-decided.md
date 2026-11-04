Label: wayfinder:grilling
Status: resolved
Parent: wayfinder-map.md

## Question

What is the scope of security for this system?

## Resolution

Full basic security layer (auth + authorization + data protection). Includes authentication, role-based authorization, session management, password hashing, input validation/sanitization, and basic protections against common vulnerabilities (CSRF, SQL injection, XSS). Not production-grade audit or encryption at rest.
