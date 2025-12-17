# Architecture Design

## Problem
Manual production deployments caused:
- Downtime
- Human errors
- No rollback mechanism

## Solution
Designed a CI/CD pipeline with:

- Git as single source of truth
- Jenkins as deployment orchestrator
- Production server isolated from developers

## Flow

Developer → GitLab → Jenkins → Production

## Why This Design?
- Security
- Repeatability
- Zero downtime
