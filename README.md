# GitHub Package Manager

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Overview

> **IMPORTANT** - This project is a work in progress with all documentation referring to a future state; it _SHOULD NOT_ be used in it's current state.

_GitHub Package Manager_ (or _GHPKG_ for convenience) is a cross platform package manager using [GitHub releases](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository) as it's catalogue and source of truth. _GKPKG_ supports releases with a [SemVer](https://semver.org/) version in their tag and has sane defaults for tag and artifact patterns.

_GHPKG_ supports stateless installations for scenarios such as container builds, and stateful installations where the package can be upgraded. _GHPKG_ is loosely inspired by [Scoop](https://scoop.sh/) but operates without any centralised package curation.

## Development

The following tasks make up the initial development of _GKPKG_.

- [ ] Filter releases by tag
- [ ] Find latest release version
- [ ] Find latest release version by constraint
- [ ] Stateless installation
- [ ] Repository configuration format
- [ ] Stateful installation
- [ ] Self-upgrade
