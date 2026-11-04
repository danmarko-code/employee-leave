# Wayfinder Map: Secure Student Employee Leave System

Label: wayfinder:map

## Destination

A modular, multi-file Python/Flask + SQLite web application for employee leave management, with full security (authentication, authorization, protected data storage), organized non-single-file code, seeded/demo data, non-generic UI built in two phases (layout/structure first, styled redesign after), delivered as a working site with source pushed to GitHub. College-grade lab activity, not production.

## Notes

- Domain: student/college lab project on secure system design; modular organization required by course practice.
- Skills to consult: grilling, domain-modeling, frontend-design (for redesign phase), codebase-design (for module organization).
- Standing preferences: simple code, easy to understand, not over-engineered; security practices must be visible (hashed passwords, session management, role-based access); UI must be non-generic; repository should be initialized on GitHub.
- Group context: repo will be shared; concurrent work possible but this session is the planning/decision driver.
- The destination is a working site, not just a spec — execution is in scope, but the map resolves decisions only.

## Decisions so far

- [Tech stack selected — Python/Flask + SQLite](tickets/tech-stack-selected.md): Flask + SQLite chosen to balance challenge and simplicity; modular file layout required.
- [Security scope: full layer (auth, authz, storage)](tickets/security-scope-decided.md): All basic security practices included (authentication, authorization, data protection, session security).
- [UI implementation approach — layout first, design second](tickets/ui-plan-approved.md): Proper grids/alignment/UX structure first; styled redesign after functionality is complete; frontend-design skill to be used for redesign phase.

## Not yet specified

- Which exact features belong in the leave system (core leave actions, manager approval workflow, dashboard/reporting, notifications/status tracking, user/role management) — depends on feature research.
- Authentication details (session vs token, password hashing library, role structure — employee/manager/admin).
- Database schema and relationships (leave requests, balances, users, approvals).
- How the UI layout structure should organize screens (dashboard, request form, approval queue, admin view).
- Which modules/files organize the code (auth, models, routes, templates, static).
- GitHub repo setup details (visibility, README, seed data script).
- Whether any feature is out of scope for the first working version.

## Out of scope

- Production deployment / hosting (college lab only; run locally or via simple server).
- Real employee data / integration with HR systems (seeded/demo data only).
- Complex notification systems (email/SMS) — basic in-app status sufficient for first version.
- Mobile-native app (web only).
- Advanced audit logging beyond basic security practice.
