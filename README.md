# mid2bms\_net

## Deploy

```bash
yarn install

TMPDIR=$(mktemp -d) ; rm -rf dist/ ; cp -R * $TMPDIR ; mv $TMPDIR dist/
yarn gh-pages -d dist/
```
