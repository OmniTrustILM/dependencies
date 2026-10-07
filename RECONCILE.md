# Reconcile before merging to main

Scope: `integration/spring-boot-4.1`. The merge commit deletes this file; if it still exists on `main`, the merge skipped these checks.

## Overrides

Each override in `pom.xml` names what it fixes and the managed version that ends it. Before the merge, delete every override the parent now manages at or above that version.
