# pi-session-id

Shows the active Pi session ID in the footer, in square brackets with the theme's dim color. Sets the status when a session starts.

## Install

```bash
pi install git:github.com/ryanmazzolini/pi-session-id
```

Run `/reload` or restart Pi after installation.

Requires Node.js 24 or newer and Pi. No package configuration is needed.

Do not load both this package and the original session-id extension.

## Development

```bash
npm install --ignore-scripts
npm test
```

`npm test` runs strict TypeScript checking, then the existing Node.js test. Test files are excluded from the package tarball.

## Provenance and license

The implementation and test were extracted unchanged from [`pi-skills`](https://github.com/ryanmazzolini/pi-skills), where their earlier history remains.

MIT. See `LICENSE`.

AI assistance was used to extract and document this package.
