# Integration ESB ADR
1. [Status](#status)
2. [Context](#context)
3. [Decision](#decision)

<a id="status"></a>
## Status
proposed
<a id="context"></a>

## Context
The client environment has several services that use different types of integration interfaces, which add a high level of complexity for managing these endpoints.
<a id="decision"></a>
## Decision
Use IBM App Connect as EBS for these reasons:
- This middleware has a lot of connectors that support different types of integration APIs.
- Some of the client services use IBM MQ, which is supported natively by this solution.