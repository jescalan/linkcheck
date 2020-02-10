# LinkCheck

NPM package wrapper for [filiph/linkcheck](https://github.com/filiph/linkcheck). Exposes only a binary that can be used to run the latest executable. Version updated occasionally, npm version pinned to the dart registry version. This simply makes the package easier to consume if it's being used as part of a node project. If you'd like to update the version, feel free to send in a PR!

### Usage

- `npm i dart-linkcheck -D`
- In your `package.json` under `scripts`, add `linkcheck: 'linkcheck'`
- Run it with `npm run linkcheck -- <args>`
