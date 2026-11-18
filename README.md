# Saymanhwa

Paperback **0.9** extension for [saymanhwa.net](https://saymanhwa.net). Adt only.

This repo follows the official Paperback 0.9 source layout used by Inkdex and similar registries: TypeScript source under `src/<Id>/` with `pbconfig.ts`, `main.ts`, and `static/icon.png`, bundled by `@paperback/toolchain` `1.0.0-alpha.92`.

## Install in Paperback 0.9

1. Enable adult sources in Paperback settings.
2. Add this repository:

```
https://vyrnexis-e16s.github.io/saymanhwa-extension/
```

3. Install **Saymanhwa**.

`paperback://addRepo?url=https://vyrnexis-e16s.github.io/saymanhwa-extension/`

## What it scrapes

- Discover: `/en/popular`, `/en/latest`
- Search: `/en/series?q=`
- Title: `series-v72` layout
- Reader: public `div.reader-pages > img` pages

VIP / login chapters are not unlocked.

## 0.9 example repos this layout matches

- [inkdex/template-extensions](https://github.com/inkdex/template-extensions)
- [inkdex/general-extensions](https://github.com/inkdex/general-extensions)
- [TheNetsky/netskys-extensions](https://github.com/TheNetsky/netskys-extensions)
- [Nicartjay/PaperbackExt](https://github.com/Nicartjay/PaperbackExt)
- [Paperback-iOS/extensions-default](https://github.com/Paperback-iOS/extensions-default)

## License

GPL-3.0-or-later
