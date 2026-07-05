# Synapse Registry

The **Synapse Registry** is the official package registry for the Synapse ecosystem.

This repository serves as the package source for the Synapse package manager. It hosts package databases, package files, and the static content required to publish the registry through GitHub Pages.

## Purpose

The Synapse Registry is responsible for:

* Publishing official Synapse packages.
* Hosting package databases.
* Providing package information for the Synapse package manager.
* Serving registry content through GitHub Pages.

## Current Repository Structure

```text
.
├── synapse-core/   # Core package database and packages
├── .gitignore
├── .nojekyll
├── index.html
└── README.md
```

As the Synapse ecosystem grows, additional repositories (such as extra, testing, or community repositories) may be added to this registry.

## Related Repositories

| Repository          | Purpose                                  |
| ------------------- | ---------------------------------------- |
| `.github`           | Organization profile and community files |
| `synapse-workspace` | Active development and source code       |
| `synapse-registry`  | Official package registry                |

---

**Synapse Registry** is the authoritative source that the Synapse package manager uses to discover, download, and update official Synapse packages.
