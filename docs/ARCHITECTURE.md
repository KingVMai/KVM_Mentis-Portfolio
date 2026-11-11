# Kingdom Mentis — architecture overview

The private prototype uses a local browser interface (HTML/CSS/JavaScript) and Python application services.

Conceptual workflow:

1. Human owner defines requirements, priorities and approvals.
2. The local WebApp presents project structure, status and selected actions.
3. The governance/control plane checks authority for governed operations.
4. KVM Core coordinates an authorized task and Dwarf executes it.
5. An independent Knight checks the result in the recorded lifecycle scenario.
6. Private operational evidence records verification, archiving and lifecycle closure.

The project hierarchy uses **Kingdom → Province → County**. This is a public conceptual explanation, not documentation of private APIs, internal source code or deployment configuration.

**Scope boundary:** No public SaaS, proven multi-tenant isolation or production security certification is claimed. Cloud First is a future architectural direction.
