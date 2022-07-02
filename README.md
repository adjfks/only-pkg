# only-you

> force constraint package manager

## Usage

Add a `preinstall` script to your project's `package.json`.

If you want to force [npm](https://docs.npmjs.com/cli/npm), add:
```
 {
    "scripts": {
      "preinstall": "npx only-pkg npm"
    }
  }
```
   

If you want to force [pnpm](https://pnpm.js.org/), add:

```
    {
      "scripts": {
        "preinstall": "npx only-pkg pnpm"
      }
    }
```

If you want to force [yarn](https://yarnpkg.com/), add:

```
    {
      "scripts": {
        "preinstall": "npx only-pkg yarn"
      }
    }
```

## License

[MIT](LICENSE)
