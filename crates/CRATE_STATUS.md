# Crate stability status

This document tracks the stability level of each crate in the Tempo workspace.

| Crate             | Stability | Notes |
|-------------------|-----------|-------|
| `tempo-core`      | stable    | Core consensus and data types. Breaking changes require an RFC. |
| `tempo-mempool`   | unstable  | API surface may change; used by experimental features. |
| `tempo-rpc`       | beta      | Suitable for integration; expect minor breaking changes. |
| `tempo-tests`     | internal  | Not published; used only for workspace tests. |

**Key**

- **stable** – API is mature; breaking changes are rare and require a major version bump.
- **beta** – Reasonably stable but subject to minor changes as feedback is incorporated.
- **unstable** – Early stage or experimental; APIs will change.
- **internal** – Crate is not intended for external consumption.

Please update this table when adding new crates or changing stability.
