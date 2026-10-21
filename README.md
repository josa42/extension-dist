# extension-dist

Signed Firefox builds of my browser extensions, served by GitHub Pages at
`https://josa42.github.io/extension-dist/`. CI of each extension pushes here
through the `shared-extension-publish` workflow of
[josa42/actions](https://github.com/josa42/actions); nothing is edited by
hand.

Each extension has a folder:

| File | |
| --- | --- |
| `<name>/<name>.xpi` | The newest version, for install links |
| `<name>/<name>-<version>.xpi` | Every published version |
| `<name>/updates.json` | Update manifest, the `gecko.update_url` of the extension |
| `<name>/chrome.json` | Version and link of the unlisted Chrome Web Store item |
