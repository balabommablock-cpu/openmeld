---
id: service-connection-lookups-and-history
title: Keep Computer connection checks responsive during release-policy refresh
kind: fixed
areas: ["computers", "agents"]
audiences: ["users", "integrators"]
---

OpenMeld can report a registered Service and its Agent routes while the release
policy is still loading. The Service keeps pending connection history on the
computer when its connection closes and resumes uploads after the new connection
is acknowledged.
