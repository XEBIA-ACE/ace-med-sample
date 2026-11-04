# Tasks: SCAFFOLD-SRV-001

- [ ] T001 Set up the project skeleton for this stack: dependency manifest, entrypoint, and linting/formatting config.
- [ ] T002 Add environment-based configuration loading (no hardcoded secrets or endpoints).
- [ ] T003 Add a health-check endpoint so the service can be verified as running locally.
- [ ] T004 Add a database connection helper for the stack's datastore, configured via environment variables.
- [ ] T005 Verify AC-1: Scaffold the User Management Service (business) per its approved architecture. Technology stack: Node.js, Express, MongoDB, JWT, OAuth 2.0, Redis. Responsibilities: User registration and authentication; Role-based access control; User profile management; Session management; Password reset and account recovery; User preference storage. Ground the generated spec in this service's own C3/C4 diagrams and API spec already on file in Architecture, not just this summary.