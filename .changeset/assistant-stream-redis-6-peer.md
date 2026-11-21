---
"assistant-stream": patch
---

The optional `redis` peer range now accepts node-redis 6, the version the package's own tests and the resumable-stream example run against. npm no longer fails with ERESOLVE when a project installs `assistant-stream` alongside `redis@6`.
