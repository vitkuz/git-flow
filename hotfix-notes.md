# Hotfix: Critical Timeout Issue

## Issue
Production servers were crashing due to indefinite request timeouts

## Solution
Added max request timeout of 30 seconds to prevent server lockups

## Affected Files
- config.md: Added timeout configuration

## Testing
- Verified timeout prevents server crashes
- No impact on normal operations

## Deployment
- Direct to production via hotfix branch