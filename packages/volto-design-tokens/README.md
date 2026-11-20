# @eeacms/volto-design-tokens

[![Releases](https://img.shields.io/github/v/release/eea/volto-design-tokens)](https://github.com/eea/volto-design-tokens/releases)
[![Pipeline](https://ci.eionet.europa.eu/buildStatus/icon?job=volto-addons%2Fvolto-design-tokens%2Fmaster&subject=master)](https://ci.eionet.europa.eu/view/Github/job/volto-addons/job/volto-design-tokens/job/master/display/redirect)
[![Coverage](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens&metric=coverage)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens)

[Volto](https://github.com/plone/volto) Design Tokens

## Features

Provides the following [EEA design system tokens](https://eea.github.io/):
   * borders
   * colors
   * fonts
   * shadows
   * shapes
   * sizes
   * z-index

## Upgrade

### Upgrading to 3.x

> This version requires `Volto 18` or `Volto 19` and Node.js 22.

The token files keep their names, their paths and their variables: every `.less` file in `src/` is
byte-identical to 2.x, so a project that imports `@eeacms/volto-design-tokens/src/tokens.less` or any
of its siblings keeps the same styles. The release adds Volto 19 support and moves the repository to
the Volto 19 layout, where the published package lives in `packages/volto-design-tokens`.

#### Breaking changes

- **Node.js 22 or newer is required** (`engines.node >= 22`), 2.x declared no engine.
- **React 18 is required.** The package declares `react` and `react-dom` as `^18.2.0` peers, 2.x
  declared no peers.
- **The package no longer ships the repository tooling.** The Jest setup is gone and the unit tests
  moved to Vitest next to the add-on, so nothing a site imports was removed.

## Requirements

### Backend

- [Plone](https://plone.org/download)
- [plone.restapi](https://pypi.org/project/plone.restapi/)

### Frontend

- Node.js: `>=22.0.0`

## Installation

1. Make sure you have a [Plone backend](https://plone.org/download) up-and-running at http://localhost:8080/Plone

   ```Bash
   docker compose up backend
   ```

1. Start Volto frontend

* If you already have a volto project, just update `package.json`:

   ```JSON
   "dependencies": {
       "@eeacms/volto-design-tokens": "*"
   }
   ```

   and `volto.config.js`:

   ```JavaScript
   const addons = ['@eeacms/volto-design-tokens'];
   ```

* If not, create one with Cookieplone, as recommended by the official Plone documentation for Volto 18+:

   ```
   uvx cookieplone project
   cd project-title
   ```

1. Install or update dependencies, then start the project:

   ```
   make install
   ```

   For a Cookieplone project, start the backend and frontend in separate terminals:

   ```
   make backend-start
   make frontend-start
   ```

1. Go to http://localhost:3000

1. Happy editing!

## License

See [LICENSE.md](LICENSE.md) for details.

## Funding

[European Environment Agency (EU)](http://eea.europa.eu)
