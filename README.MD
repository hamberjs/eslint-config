## ESLint configuration

Common eslint configuration for the Hamber organisation

## Contributing

Want to add an eslint rule? Open a PR and use gh-polls for voting: https://app.gh-polls.com/

## Usage

Installation:

```bash
npm i -D eslint hamberjs/eslint-config
```

### Node Modules

In your project's package.json, use the shorthand syntax

```json
  "eslintConfig": {
    "extends": "@hamberjs"
  }
```

## Linting

This project self-lints:

```bash
npm i
npm run lint
```

## Releasing

To release a new version, check out the code on your local machine, then:

```bash
npm version minor
git push && git push --tags
```

Where `minor` is a sensible default for rule changes which will impact existing projects.
