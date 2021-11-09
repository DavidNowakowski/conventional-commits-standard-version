# Conventional commits standard version

This is an example of [conventional commits standard](https://www.conventionalcommits.org/en/v1.0.0/) + [changelong/standard-version](https://github.com/conventional-changelog/standard-version) tool.

## Benefits

- Standard for the commits message format. Helps to developers to follow a structure
 easy to understand.

- It is built on the top of semver so also follows this standard.

- Can calculate and generate automatically the next version and CHANGELOG.md.

- There are many [open source tools](https://www.conventionalcommits.org/en/about/) to helps us such as lints, changelogs generators or next version calculators already available.

## Main commands

Release with:

```bash

npx standard-version run release

´´´

Release candidate with:

```bash

npx standard-version run --prerelease RC

´´´