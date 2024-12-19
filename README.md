# Documentation for Dapplet Platform

[](https://github.com/dapplets/dapplet-docs/blob/master/README.md#documentation-for-dapplet-platform)

Documentation for the Dapplet Platform. Includes instructions for using the [Dapplet Browser Extension](https://github.com/dapplets/dapplet-extension), [exercises](https://github.com/dapplets/dapplet-template) for creating dapplets and adapters for the platform, and documentation for community-created adapters.

View at [dapplets.mintlify.app](https://dapplets.mintlify.app)

## Node Version

[](https://github.com/dapplets/dapplet-docs/blob/master/README.md#node-version)

You must use **node 14** or above. We recommend [nvm](https://github.com/nvm-sh/nvm).

## Installation

`yarn install`

## Local Development

[](https://github.com/dapplets/dapplet-docs/blob/master/README.md#local-development)

`yarn start`

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

## Build

[](https://github.com/dapplets/dapplet-docs/blob/master/README.md#build)

`yarn build`

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

[](https://github.com/dapplets/dapplet-docs/blob/master/README.md#deployment)

`GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy`

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.