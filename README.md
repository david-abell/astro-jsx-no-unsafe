# Astro Minimal reproduction repo for no unsafe return and JSX

[eslint-plugin-astro issue #168](https://github.com/ota-meshi/eslint-plugin-astro/issues/168#issue-1589581316)

## Steps to reproduce

Run `package.json` script `lint`

Expected output

```bash
dir...\astro-jsx-no-unsafe\src\pages\index.astro
  34:11  error  Unsafe return of an `any` typed value  @typescript-eslint/no-unsafe-return
  41:11  error  Unsafe return of an `any` typed value  @typescript-eslint/no-unsafe-return
```
