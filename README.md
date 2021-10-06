# Oriflame/renovate-config

Renovate config presets used primarily by Oriflame in Azure devops.

## Presets

- default
  - Default configuration with configuration for azure
- frontendRecommended
  - Recommended setting for frontend repositories
- frontendLazy
  - Lazy settings that updates all dependencies at once

## Usage

```json
// Renovate config
{
  "extends": [
    "github>oriflame/renovate-config",
    "github>oriflame/renovate-config:frontendRecommended",
    "github>oriflame/renovate-config:frontendLazy"
  ]
}
```
