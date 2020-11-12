# Contributing

## Build

### Start

    develop$ git-flow release start 4.5.3-rc3

## Dist

    npm run dist

Commit

## Doc

Update README.md, [docs/index.html] if necessary.

### Finish 

    develop$ git flow release finish '4.5.3-rc3'

## Release

Go to github and create a release

## Publishing

Setup a `NPM_AUTH_TOKEN`env var used in `.npmrc`

Then:

    npm publish --access=public