# @job-platform/prettier-config

Shared Prettier configuration for the Job Platform project.

## Usage

1. Install the package in your project:

```bash
pnpm add -D @job-platform/prettier-config
```

2. Create a `prettier.config.js` file in your project root and extend this configuration:

```js
module.exports = require('@job-platform/prettier-config')
```

## Configuration

This configuration includes our standard Prettier rules:

- Single quotes for strings
- No semicolons
- 2 spaces indentation
- 95 characters line length
- Trailing commas
- And more...

For the full configuration details, see the `index.js` file.
