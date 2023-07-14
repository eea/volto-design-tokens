# volto-design-tokens

[![Releases](https://img.shields.io/github/v/release/eea/volto-design-tokens)](https://github.com/eea/volto-design-tokens/releases)

[![Pipeline](https://ci.eionet.europa.eu/buildStatus/icon?job=volto-addons%2Fvolto-design-tokens%2Fmaster&subject=master)](https://ci.eionet.europa.eu/view/Github/job/volto-addons/job/volto-design-tokens/job/master/display/redirect)
[![Lines of Code](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-master&metric=ncloc)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-master)
[![Coverage](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-master&metric=coverage)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-master)
[![Bugs](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-master&metric=bugs)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-master)
[![Duplicated Lines (%)](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-master&metric=duplicated_lines_density)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-master)

[![Pipeline](https://ci.eionet.europa.eu/buildStatus/icon?job=volto-addons%2Fvolto-design-tokens%2Fdevelop&subject=develop)](https://ci.eionet.europa.eu/view/Github/job/volto-addons/job/volto-design-tokens/job/develop/display/redirect)
[![Lines of Code](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-develop&metric=ncloc)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-develop)
[![Coverage](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-develop&metric=coverage)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-develop)
[![Bugs](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-develop&metric=bugs)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-develop)
[![Duplicated Lines (%)](https://sonarqube.eea.europa.eu/api/project_badges/measure?project=volto-design-tokens-develop&metric=duplicated_lines_density)](https://sonarqube.eea.europa.eu/dashboard?id=volto-design-tokens-develop)


[Volto](https://github.com/plone/volto) add-on

## Features

Demo GIF

## Getting started

### Add volto-design-tokens to your Volto project

1. Make sure you have a [Plone backend](https://plone.org/download) up-and-running at http://localhost:8080/Plone

1. Start Volto frontend

* If you already have a volto project, just update `package.json`:

   ```JSON
   "addons": [
       "@eeacms/volto-design-tokens"
   ],

   "dependencies": {
       "@eeacms/volto-design-tokens": "*"
   }
   ```

* If not, create one:

   ```
   npm install -g yo @plone/generator-volto
   yo @plone/volto my-volto-project --canary --addon @eeacms/volto-design-tokens
   cd my-volto-project
   ```

1. Install new add-ons and restart Volto:

   ```
   yarn
   yarn start
   ```

1. Go to http://localhost:3000

1. Happy editing!

## Release

See [RELEASE.md](https://github.com/eea/volto-design-tokens/blob/master/RELEASE.md).

## How to contribute

See [DEVELOP.md](https://github.com/eea/volto-design-tokens/blob/master/DEVELOP.md).

## Copyright and license

The Initial Owner of the Original Code is European Environment Agency (EEA).
All Rights Reserved.

See [LICENSE.md](https://github.com/eea/volto-design-tokens/blob/master/LICENSE.md) for details.

## Funding

[European Environment Agency (EU)](http://eea.europa.eu)
