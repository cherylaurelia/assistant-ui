---
"assistant-ui": patch
---

`create` no longer reports success when a scaffolded file imports a registry path (`@/components/…`, `@/hooks/…`, `@/lib/utils`) that no installed file provides. It lists those imports, says how to add a missing components.json, prints the component install command to rerun, and exits 1, as it already does when shadcn exits non-zero.
