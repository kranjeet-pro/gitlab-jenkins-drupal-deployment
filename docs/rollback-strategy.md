# Rollback Strategy

## Problem
Bad deploy can break production.

## Solution
- Each deployment creates a versioned release
- Live site points to a symlink (`current`)
- Rollback = symlink switch

## Benefits
- Instant rollback
- No downtime
- No DB impact
