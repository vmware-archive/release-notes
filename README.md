# Concourse release notes

This repository contains the [Booklit](https://vito.github.io/booklit)
documents and templates for generating Concourse's release notes.

These are kept in a separate repo from the docs so that the docs can be
versioned. Release notes are global and have a single source of truth, so
tracking them alongside the rest of the docs doesn't really make sense.

They do however *depend* on the Concourse docs so that they can the docs can be
referenced and linked to from the release notes.

## Rendering the release notes

```bash
./scripts/build VERSION
```
