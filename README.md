# online-renovate-config

This repository contains the renovate configuration for all repositories of the online-block team. It should be used by all repository to have a consistent automatic dependency management.

## Integration

1. Reference it in your `renovate.json`:
```
{
  "extends": ["@technik-sde"]
}
```

## Publishing

1. Bump the version via:
```
npm version major|minor|patch
```

2. Commit and Push it to the main Branch (via PR), it will be published via GitHub action pipeline
