# Challenges & Fixes

## SSH Permission Issues
- Problem: Jenkins could not connect to prod
- Fix: Proper SSH key trust & permissions

## Vendor Directory Conflict
- Problem: Vendor path mismatch
- Fix: Central shared vendor with symlink

## Zero Downtime Requirement
- Solution: Atomic releases with symlink switch
