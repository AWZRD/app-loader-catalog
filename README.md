# App Loader catalog

Static GitHub Pages site for [App Loader](https://github.com/). Hosts `catalog.json` plus the IPAs and manifests it points to.

## Layout

```
catalog.json                          ← the index App Loader fetches
apps/
  <app-id>/
    icon.png
    <version>/
      <AppName>.ipa
      manifest.plist
```

See `../PUBLISHING.md` in the App Loader project for the full publish flow.
