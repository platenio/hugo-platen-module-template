# hugo-platen-module-template

A GitHub template for starting a new module.

What follows is some boilerplate for your readme:

## Overview

## Requirements

- Hugo `0.92.2` or higher
- Hugo extended version, read more [here](https://gohugo.io/news/0.48-relnotes/)

## Features

### Shortcodes

### Layouts

## Installation

First, you'll need to update your site configuration to add this module:

```yaml
# config.yaml
module:
  imports:
    - path: github.com/organization/repository
```

Next, you'll need to try to serve your site - this should automatically pull in the module with default settings!

```sh
hugo serve
```

## Configuration

The configuration options for MODULE NAME include:

- This
- That
- The Other

### Full Configuration Example

```yaml
params:
  MyModule:
    # MyConfig does something
    MyConfig: bar
```

## Versioning

This theme follows [semantic versioning], e.g. `v1.0.0`.
It also includes shorthand tags like `v1` and `v1.1` for if you want to pin to a major or minor version.
If you prefer to get all the latest changes, including the dangers of breaking changes, you _can_ pin to `main` instead.

## Contributing

This project is open to improvements and fixes; we take issues and PRs alike and thank you for them!
