# [@valudio/tslint-rules](https://github.com/valudio/tslint-rules) &middot; ![Release](https://github.com/valudio/tslint-rules/workflows/Release/badge.svg) [![npm version](https://img.shields.io/npm/v/@valudio/tslint-rules.svg?style=flat)](https://www.npmjs.com/package/@valudio/tslint-rules)

TSLint rules for TypeScript projects at Valudio.

## Usage

```
npm i @valudio/tslint-rules
```

Then add this tslint.json:

```json
{
  "extends": ["@valudio/tslint-rules"],
  "linterOptions": {
    "exclude": [
      "**/*.css",
      "**/*.scss",
      "**/*.svg",
      "**/*.js",
      "**/serviceWorker.ts"
    ]
  }
}
```
