# qapp-learning-content

Public JSON lesson bundles for **QAPP Mobile** (Quranic Arabic PWA).

## CDN base (jsDelivr)

Use this as `content-source` in the app:

```
https://cdn.jsdelivr.net/gh/neospark-sol/qapp-learning-content@main/content
```

## manifest.json

- `contentBundleTag` — release label (e.g. \`1.0.0\`).
- `loaderSchemaVersion` — client must support this schema.
- Each file has `rev` (increments when that file changes); clients fetch only files with a higher `rev` than cached.

Edit source JSON in the app monorepo, run \`npm run sync\`, then copy \`content/\` here and push.
