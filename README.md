# renovate-config

This repository contains the renovate configuration for all repositories of the online-block team. It should be used by all repository to have a consistent automatic dependency management.

## Integration

1. Reference it in your `renovate.json`:

```
{
  "extends": ["github>sueddeutsche/online-renovate-config"]
}
```

## Respository

Renovate only has access to selected repositories.
When you add a new repository to renovate make sure to update the access as well:
https://github.com/apps/renovate/installations/new
