# parcel-plugin-nunjucks
[Parcel](https://parceljs.org/) plugin to compile [Nunjucks](https://mozilla.github.io/nunjucks/) templates.

## Feature of this fork
The context passed to `nunjucks.renderString()` is either a `global.json` or `context.json` file located in `./src/html/`. Intended for simple content generation, not configuration.
