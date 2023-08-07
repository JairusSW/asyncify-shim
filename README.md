# Asyncify

**A small lib that adds Asyncify support for AssemblyScript**

## Installation

Install from NPM

```
~ npm install asyncify-shim
```

Add a `--transform asyncify-shim` flag to your `asc` command.
Alternatively, add it to your `asconfig.json`.

```
{
  // ...
  "options": {
    "transform": ["asyncify-shim"]
  }
}```