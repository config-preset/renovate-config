# Renovate Config

Shared Renovate Bot Config Preset

## Usage

Add the following to your `.github/renovate.json` file:

```jsonc
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>config-preset/renovate-config"
  ],
  // override any settings here
  "automerge": true
}
```