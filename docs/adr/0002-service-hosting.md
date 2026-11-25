# 0002. Service hosting environment

**Status:** Accepted

## Context

We need a consistent and isolated environment to run the Notes API service across development and testing.

## Decision

The service runs inside a Docker container based on Python 3.12, exposing port 8000 (or 9000 as configured in the runbook).

## Consequences

The application behaves identically on every developer machine and server without dependency conflicts.
